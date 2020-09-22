# 标题
## 标题2
### 标题3

> 这段文字将高亮显示
> 区块
>> 区块2
>>> 区块3

[link](http://www.baidu.com)
![图片](http://)

##### 列表
* aaa
    * bbb
        * ccc

+ ddd
    + eee
        - fff
            - ggg

1. First
    * A
2. Second
    - B
3. Third
    + C


> 分割线
***
分割线2
___
* * *
- - -
*************
-------------

*这里是斜体*
_这里也是斜体_

**这里是加粗**
__这里是加粗__

~~这里是删除线~~

<u>这里是下划线</u>

这里是脚注 [^MIY]


插入代码
`printf("%d", a)`

插入代码块

    int main() {
        int a = 0;
        cout << a << endl;
    }

插入代码块2(语法高亮)
```C++
void inorder(TreeNode* root) {
    inorder(root->left);
    //do something
    inorder(root->right);
}
```

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

**转译**
\* \+ \- \_ \\ \{ \} \# \. \! 

**公式**
$f(x) = x^2+2x + 1$
