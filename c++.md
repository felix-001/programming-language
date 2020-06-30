# 数据类型
## string
### 初始化
```
string s = "foo";
string s("foo");
string s1(s);// 使用另一个string去初始化当前string
string s = s1 + s2;
string s(s1, pos, num);// 从ts1中的第pos个位置开始，拷贝个数为num个字符
string s = s1.substr(); //参数列表为空则会拷贝s1的整个对象（复制s1的简便方法）
```
