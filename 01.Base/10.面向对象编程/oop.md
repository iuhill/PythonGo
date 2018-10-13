# 0 Python面向对象OOP
- Python面向对象
- 面向对象编成
    - 基础
    - 公有私有
    - 继承
    - 组合，Minxi
- 魔法函数
    - 魔法函数概述
    - 构造类魔法函数
    - 运算类魔法函数
    
# 1 面向对象概述
- OOP思想
    - 模型
-OO——ObjectOriented
- OOA分析
- OOD设计
- OOI实现
- OOP编程
- OOA——OOD——OOP

# 2 类和对象的概念
    - 类:抽象，具有属相和方法
    - 对象:具象 
    - 类的命名
        - 变量命名规范
        - 大驼峰
        - 避开系统保留词
    - class关键字
    - case v1.py
# 3 类和对象成员分析
- 类实例
- 对象实例
# 4 self
- self不是关键字，只是占用参数的第一个位置，表示对象本身

- 非绑定类方法，参数中有self
- 绑定类方法，参数中没有self，只能通过类访问

# 4 面向对象的三大特性
- 封装:访问限制——public,protected,private
    - public,protected,private并非关键字，只是设计思想
    - __attribute，私有变量，只能在当前类或对象中访问:_classname_attribute
    - _attribute,受保护变量，只能在当前类和子类中访问
    - attribute,公共变量，所有位置都可以访问
- 继承:不重复造轮子，拿来主义
    - is-A关系:subclass IS superclass
    - 子类可以扩充父类方法的功能——super().父类成员属性
- 多态:同一对象在不同情况下，有不同的状态出现
- Mixin——掺入
    - 主要采用多继承的方式，进行类的功能扩展
    - 必须表示某单一功能，而不能是某个物品，功能单一
    - 仅用来扩展的单一功能类