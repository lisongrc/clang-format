# .clang-format
.clang-format文件，Xcode自定义代码格式化样式文件。

文件内容如下，也可以自己修改。具体讲解可以看我在简书上写的[这篇文章]()。
```
# 基于LLVM样式
BasedOnStyle: LLVM

# 连续的赋值操作按=对齐，看自己喜好打开。
#AlignConsecutiveAssignments: true

# 把连续行的变量名对齐，看自己喜好打开。
#AlignConsecutiveDeclarations: true

# 对齐尾部注释
AlignTrailingComments: true

# 大括号前面是否换行
BreakBeforeBraces: Allman

# 每行字符的宽度不限制
ColumnLimit: 0

# 缩进宽度设置为4
IndentWidth: 4

# switch的case缩进宽度
IndentCaseLabels: true

# 不保留block里面开始的空行们
KeepEmptyLinesAtTheStartOfBlocks: false

# 最多只能有连续1行空行
MaxEmptyLinesToKeep: 1

# 在@property后加空格
ObjCSpaceAfterProperty: true

# 尾部//注释前面加1个空格
SpacesBeforeTrailingComments: 1

# 在<后边和>前边插入空格
SpacesInAngles: true
```
