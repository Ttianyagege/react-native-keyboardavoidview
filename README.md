# react-native-keyboardavoidview
基于React Native封装的表单提交Container，用于替代RN官方组件KeyboardAvoidingView(不兼容Android)

## Installation

```bash
npm install react-native-keyboardavoidview --save
```

## Import into your project
```js
import KeyboardAvoidingView from 'react-native-keyboardavoidview';
```

## Examle useage

```js
<KeyboardAvoidingView>
    <TextInput style={Styles.textInput} placeholder='课程标题' placeholderTextColor={Colors.C5} />
    <TextInput style={Styles.textInput} placeholder='简介' placeholderTextColor={Colors.C5} />
    <TextInput style={Styles.textInput} placeholder='人数上限' placeholderTextColor={Colors.C5} keyboardType='numeric' />
    <TextInput style={Styles.textInput} placeholder='课程标题' placeholderTextColor={Colors.C5} />
    <TextInput style={Styles.textInput} placeholder='简介' placeholderTextColor={Colors.C5} />
    <TextInput style={Styles.textInput} placeholder='活动地点' placeholderTextColor={Colors.C5} />
</KeyboardAvoidingView>
```

## Properties
属性  | 描述    | 类型  | 默认    
------ | ------ | ------  | ------
style  | container样式 | ```PropTypes.oneOfType([ ViewPropTypes.style, PropTypes.number ]) ``` | ``` { flex: 1, backgroundColor: '#F7F7F7', paddingLeft: 15 } ```
