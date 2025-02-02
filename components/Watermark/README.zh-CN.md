`````
组件 / 反馈

# 水印 Watermark


水印组件，`2.56.0` 支持
`````


%%Content%%

## API

### Watermark

`2.56.0` 支持

|参数名|描述|类型|默认值|
|---|---|---|---|
|rotate|单个水印旋转角度|number |`-20`|
|content|水印的文字内容|string |`-`|
|image|水印图片源，优先级比文字内容高|string |`-`|
|className|节点类名|string \| string[] |`-`|
|fontStyle|水印文字样式|{color?: string;fontFamily?: string;fontSize?: number \| string;fontWeight?: number \| string;} |`{color:`rgba(0, 0, 0, 0.12)`, fontFamily: `sans-serif`, fontSize: `14px`, fontWeight: `normal` }`|
|gap|水印间的间距|[number, number] |`[100, 100]`|
|height|单个水印的高度|number \| string |`-`|
|offset|水印相对于 `container` 容器的偏移量。|[number, number] |`[`gaps[0] / 2`, `gaps[1] / 2`]`|
|style|节点样式|CSSProperties |`-`|
|width|单个水印的宽度。`image` 时默认为 100，content 时默认为文本宽度|number \| string |`-`|
|zIndex|zIndex|string \| number |`-`|
|getContainer|添加水印的容器 `wrapper`，会把水印 `dom` 作为 `container` 的第一个子节点展示|() => HTMLElement |`-`|
