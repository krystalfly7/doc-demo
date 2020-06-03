# 用户手册

> upchart.
### 基础示例
```
<script>
</script>
```

## API
### Props
| 参数 | 说明 | 类型 | 可选值 | 默认值 |
|--- |--- |--- |--- |--- |
| value | 当前选中项 | array | - | - |
| no-data-text | 空数据时显示文案 | string | - | '暂无数据' |
| disabledList | 禁用节点列表 | array | [] | - |

### Events
| 事件名称 | 说明 | 回调参数 |
|--- |--- |--- |
| change | 绑定值发生变化时触发 | function (value: array, selectedOptions: array) |
| update:visible | 下拉框显示/隐藏时触发 | function (visible: boolean) |

### Methods
| 事件名称 | 说明 | 声明 |
|--- |--- |--- |
| focus() | 使 cascader 获取焦点 | function | - |
| blur() | 使 cascader 失去焦点 | function | - |
