大黄 2年半  QQ?

835814279 合格QQ

- 正则表达式  /[]/表示正则对象 RegExp
         1.用来检索，确定待检测的字符是否符合规则的对象  
         2.在JS中 除了简单类型之外 一切都是对象
         3.运算符号 用于表达规则[0-9]数字 ：/[0-9]/ 是检索符合0-9的数值，
            [a-z]小写字母
            [A-Z]大写字母
            {5，13} 可用于限定长度 从开始到结束 限界 ：/[0-9]{5,13}/.test("12569")最小长度5最大长度13
            ^匹配字符串的开始符合其代码规则， ：/^[0-9]{5,13}/.test("100086") true 
                                            :/^[0-9]{5,13}/.test("sd100086")  false
                                            ：/^[0-9]{5,13}$/.test("100086")
                                            /[0-9]{5,13}$/.test("100086")

        4.^ 字符串的开始  $字符串的结束

 -【 QQ号加密 解密】
631758924  加密  
    解码规则： 第一个数字删除，第二个数字移到末尾。后重复上操作，第三个数删除第四个数字移动到末尾，直至最后一个数删除则结束。
    631758924    -6
    17589243     - 1
    5892437       -5
    924378        9
    43782           4
    7832            7
    238             2   
    83              8
   3                 3       QQ：615947283
    


- 数组 实最廉价的数据结构  其本身是一个线性的连续存储空间，下标
    head指向头部  tail指向尾部 
    1.如果数组只在队尾插入和删除   栈是一个先进后出Last First
    2.如果是在头部删除，在尾部添加元素    队列Queue是一个先进先出


    