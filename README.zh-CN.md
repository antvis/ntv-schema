# ntv-schema

<img src="https://gw.alipayobjects.com/zos/antfincdn/R8sN%24GNdh6/language.svg" width="18"> [English](./README.md) | 简体中文

数据解读文本规范的 JSON 描述文件，可用于（[@antv/ava-react NarrativeTextVis](https://github.com/antvis/AVA/blob/master/packages/ava-react/zh-CN/README.zh-CN.md)）。

## Url 格式

```
https://antv.github.io/text-schema/[version].json
```

[version]定义您获取架构的库的版本。未指定版本匹配未指定部分的最新版本。例如 v1 匹配最新的主要版本，v1.1 匹配最新的次要版本，v1.1.1 匹配一个确切的版本。
例如 https://antv.github.io/text-schema/v3.json 将提供 https://vega.github.io/text-schema/v3.0.0.json。
