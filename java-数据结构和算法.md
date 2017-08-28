```java
java.util.Collection [I]
    +--java.util.List [I]
       +--java.util.ArrayList [C]    
       +--java.util.LinkedList [C]  
       +--java.util.Vector [C]    //线程安全 弃用
          +--java.util.Stack [C]  //线程安全
    +--java.util.Set [I]                   
       +--java.util.HashSet [C]      
       +--java.util.SortedSet [I]    
          +--java.util.TreeSet [C]    
    +--Java.util.Queue[I]
        +--java.util.Deque[I]   LinkedList实现
        +--java.util.PriorityQueue[C]  
java.util.Map [I]
    +--java.util.SortedMap [I]
       +--java.util.TreeMap [C] //排好序到集合
    +--java.util.Hashtable [C]   //线程安全
    +--java.util.HashMap [C] //用ConcurrentHashMap代替
    +--java.util.LinkedHashMap [C] //有序
    +--java.util.WeakHashMap [C]

[I]：接口
[C]：类
```