---
title: tag
subtitle: 热门标签
type: Widgets
---

进行标记标签，**注：** 只支持 `checkable` 标签模式。

## API

### schema 属性

参数 | 说明 | 类型 | 默认值
----|------|-----|------
`[enum]` | 数据源 | `SFSchemaEnumType[]` | -

### ui 属性

参数 | 说明 | 类型 | 默认值
----|------|-----|------
`[asyncData]` | 异步数据源 | `() => Observable<SFSchemaEnumType[]>` | -
`[afterClose]` | 关闭动画完成后的回调 | `() => void` | -
`[onClose]` | 关闭时的回调，在 `nzMode="closable"` 时可用 | `(e:MouseEvent) => void` | -
`[checkedChange]` | 设置标签的选中状态的回调 | `(status: boolean) => void` | -
