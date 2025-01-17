---
order: 1
title:
  zh-CN: 范围选择器
  en-US: Range Picker
---

## zh-CN

通过设置 `picker` 属性，指定范围选择器类型。

## en-US

Set range picker type by `picker` prop.

```jsx
import { DatePicker } from 'antd';

const { RangePicker } = DatePicker;

ReactDOM.render(
  <>
    <RangePicker enableSelectTwiceWhenClickLeft={true} />
    <br />
    <RangePicker enableSelectTwiceWhenClickLeft={true} showTime />
    <br />
    <RangePicker enableSelectTwiceWhenClickLeft={true} picker="week" />
    <br />
    <RangePicker enableSelectTwiceWhenClickLeft={true} picker="month" />
    <br />
    <RangePicker enableSelectTwiceWhenClickLeft={true} picker="year" />
  </>,
  mountNode,
);
```
