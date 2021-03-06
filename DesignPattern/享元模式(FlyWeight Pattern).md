享元模式

---

>   引用   
>
>   [享元模式](http://www.runoob.com/design-pattern/flyweight-pattern.html)
>
>   [享元模式（zuoxiaolong）]()   

---


主要用于减少创建对象的数量，以减少内存占用和提高性能。这种类型的设计模式属于结构型模式，它提供了减少对象数量从而改善应用所需的对象结构的方式。

享元模式尝试重用现有的同类对象，如果未找到匹配的对象，则创建新对象。


**主要解决**：在有大量对象时，有可能会造成内存溢出，我们把其中共同的部分抽象出来，如果有相同的业务请求，直接返回在内存中已有的对象，避免重新创建。

**应用实例**： 
1.  JAVA 中的String，如果有则返回，如果没有则创建一个字符串保存在字符串缓存池里面。 
2.  数据库的数据池。

