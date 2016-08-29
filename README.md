# react-native-guide
这个仓库记录我在rn上所踩过的坑
1.Text组件的lineHeight属性在android当中只能使int型，不能使double类型（不能带小数点）相关链接：https://github.com/facebook/react-native/issues/3715

2.TextInput组件 输入的文字开始的位置在ios中默认是从上开始，而安卓是从中间开始的，安卓可以通过他的style里的textAlignVertical属性来设置他是从哪开始的

3.关于键盘的组件 收起键盘的时候可以使用这个api：dismissKeyboard相关链接

4.在当前页面，刷新其他页面listview，返回listview页面，显示空白bug，[相关链接](https://github.com/facebook/react-native/issues/1831)

5.image在listview中更换其source并不会更换图片。[相关链接](https://github.com/facebook/react-native/issues/1397#issuecomment-105367632)
