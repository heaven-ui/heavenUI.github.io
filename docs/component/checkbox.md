#### Checkbox 多选框


#### 常用多选框。

``` html
<template>
    <h-checkbox v-model="value">多选框</h-checkbox>
</template>
```
``` js
<script>
export default {
  data() {
    return {
        value:''
    }
  },
};
</script>
```


### 配置选项
| 参数 | 说明 | 类型 | 可选值 | 默认值 |
|-|-|-|-|-|
| value / v-model | 绑定值 | string / number | - | - |
| disabled | 是否禁用状态 | String | — | — |
| readonly | 设置输入框为只读 | Boolean | — | false |