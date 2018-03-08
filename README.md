# vue-percentage
用 Canvas 实现的百分比圆环的 Vue 组件（带动画），可以自由定制颜色和尺寸。

## Usage

```
 props: {
    used: {
      required: true,
      type: Number
    },
    free: {
      required: true,
      type: Number
    },
    usedColor: {
      type: String,
      default: '#ff6100'
    },
    freeColor: {
      type: String,
      default: '#ddd'
    },
    lineWidth: {
      required: true,
      type: Number
    },
    height: {
      required: true,
      type: Number
    },
    width: {
      required: true,
      type: Number
    }
  }
```

- used: 已使用的部分
- free: 未使用的部分
- usedColor: 已使用的部分的颜色
- freeColor: 未使用的部分的颜色
- height: 高度
- width: 宽度