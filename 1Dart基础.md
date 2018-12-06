## Dart基础
以下dart代码展示了dart的大概功能：
```dart
// 定义函数
printInteger(int aNumber) {
  print('The number is $aNumber.'); // 打印到控制台
}

// 这里是app开始执行的地方
main() {
  var number = 42; // 声明且初始化变量
  printInteger(number); // 调用函数.
}
```

下面这个程序用途适用于所有Dart app：
```dart
// This is a comment.
```
单行注释。Dart同时支持多行注释和文档注释。更多查阅[Comments](https://www.dartlang.org/guides/language/language-tour#comments)
```dart
int
```
一种类型。其他[内置类型](https://www.dartlang.org/guides/language/language-tour#built-in-types)是String、List和bool.
```
42
```
数字。数字是一种编译期常量。
```
print()
```
简便的方法输出显示。
```
'...'(or "...")
```
字符串
```
$variableName (or ${expression})
```
字符串插值。查阅[Strings](https://www.dartlang.org/guides/language/language-tour#strings)
> *语法跟kotlin、scala(f"xxxx$var")是相似的*
```
main()
```
特殊、必须的顶级函数，在app启动时执行。查阅[The main() function](https://www.dartlang.org/guides/language/language-tour#the-main-function).
```
var
```
不用类型定义变量的方式.
> 注意：这个站点的代码遵循[Dart style guide](https://www.dartlang.org/guides/language/effective-dart/style)约定
