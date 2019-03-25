>### 准备工作

```flow
st=>start: 准备开始
e=>end: 准备完成
op1=>operation: 哈哈
op2=>operation: 哈哈
cond=>condition: 哈哈?

st->op1->cond
cond(yes)->e
cond(no)->op2->e
```