- HashSet，内部是用HashMap来存储数据，用HashMap的key，value填充一个无实际意义的对象。无重复元素，无顺序，允许null元素，非线程安全。迭代器fail-fast。
- LinkedHashSet，继承了HashSet，内部是用LinkedHashMap来存储数据。其他都和HashSet一样。但是内部是链表。
- TreeSet，有序Set，可以按照自然排序或者指定的Comparator进行排序。迭代器是fail-fast的。
- BitSet，海量数据的时候使用
- EnumSet，暂没看
- JumboEnumSet，暂没看
- RegularEnumSet，暂没看
- ConcurrentSkipListSet，内部使用ConcurrentSkipListMap实现，有序Set，和TreeSet作用类似，但是是线程安全的。
- CopyOnWriteArraySet，底层是基于CopyOnWriteArrayList实现
