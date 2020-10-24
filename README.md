# shortlink
PHP +VUE编写的shortlink短链接项目，简单易懂，适合初学者。


# 修改参数


# 尝试运行
npm install

增量编译
npm run serve
生产发布
npm run build

# 项目说明
这是我第二个Vue+PHP项目
不怕大家笑话，我写了5个小时。
第一个小时把后端借口大致写了
第2、3个小时在不断调试后端接口，改改代码
第4个小时构建Vue+ElementUI，不得不说是真的好用
第5个小时，就是现在，我在发布项目。

总结：
1。PHP用json_encode($arr)的时候，如果arr提前有键值对的形式，在用数字作为key的情况下，那么保存也是键值对的形式（key value）。但如果不是提前规定好了，直接上arr【】】，那么jsonencode后，就没有key了。
2。php用strpos查找，得用==false判断它没有出现。但是！如果出现的位置在第0个（即最开头出现了要查找的字符串），那么，==false是成立的！
3.vue里有时候需要把observer对象转化为json对象进行操作，可以用JSON。stringfy+JSON，parse二度操作。
