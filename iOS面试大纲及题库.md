# GoDocments


iOS技术面试考察点

1、开发语言基本知识

1.1、 Objective-C基本知识（分类、运行时、runloop，block、循环引用、KVC、KVO）

1.2、 swift 基本知识（扩展、存储属性、计算属性、enum、struct、class）

1.3、 UI控件基本知识（响应链、音视频播放）

1.4、 项目常用的架构模式：MVC、MVVM



2、 项目经验

2.1、 常用三方库的使用、实现及原理： SDWebImage、RxSwift、AFNetwork等热门库

2.2、 git使用经验，分支的管理

2.3、 项目打包上架App Store、TestFlight、企业包、超级签改签相关经验



3、优化经验

3.1、卡顿问题定位及解决

3.2、包体积大小优化

3.3、启动优化





面试题参考：
--------题库一-----------
目录：
1.进程与线程分别是什么意思？
2.什么是多线程？
3.多线程的优点和缺点有哪些？
4.多线程的 并行 和 并发 有什么区别？
5.iOS中实现多线程的几种方案，各自有什么特点？
6.多个网络请求完成后如何执行下一步？
7.多个网络请求顺序执行后如何执行下一步？
8.如何理解多线程中的死锁？
9.如何去理解GCD执行原理？

1-9跳转链接：iOS最新面试题+答案（多线程篇）
目录：
10.网络七层协议有哪些？
11.Http 和 Https 的区别？Https为什么更加安全？
12.HTTPS的连接建立流程
13.解释一下 三次握手 和 四次挥手
14.TCP 和 UDP的区别
15.Cookie和Session
16.DNS是什么？
17.DNS解析过程

10-17跳转链接：iOS最新面试题+答案（网络篇）
目录：
一，组件化
18.组件化有什么好处？
19.你是如何组件化解耦的？
20.为什么CTMediator方案优于基于Router的方案？

基于CTMediator的组件化方案，有哪些核心组成？
二，性能优化
22.造成tableView卡顿的原因有哪些？
23.如何提升 tableview 的流畅度？
24.APP启动时间应从哪些方面优化？
25.如何降低APP包的大小
26.如何检测离屏渲染与优化
27.怎么检测图层混合
28.日常如何检查内存泄露？
29.如何优化 APP 的电量？

18-29跳转链接：iOS最新面试题+答案（组件化+性能优化篇）
目录：
一，项目架构
30.MVC、MVP、MVVM模式
31.关于RAC你有怎样运用到解决不同API依赖关系
32.@weakify和我们宏定义的WeakSelf有什么区别？
33 . 微服务的架构设想

二，设计模式
34.iOS有哪些常见的设计模式?
35.单例会有什么弊端？
36.编程中的六大设计原则？
37.如何设计一个图片缓存框架？
38.如何设计一个时长统计框架？

30-38跳转链接：iOS最新面试题+答案（架构+设计模式篇）
目录：
39.Runloop 和线程的关系？
40.RunLoop的运行模式
41.runloop内部逻辑？
42.autoreleasePool 在何时被释放？
43.GCD 在Runloop中的使用？
44.AFNetworking 中如何运用 Runloop?
45.PerformSelector 的实现原理？
46.PerformSelector:afterDelay:这个方法在子线程中是否起作用？
47.事件响应的过程？
48.手势识别的过程？
49.CADispalyTimer和Timer哪个更精确？

39-49跳转链接：iOS最新面试题+答案（Runloop篇）
目录：
50.Category 的实现原理？
51.isa指针的理解，对象的isa指针指向哪里？isa指针有哪两种类型？
52.Objective-C 如何实现多重继承？
53.runtime 如何实现 weak 属性？
54.讲一下 OC 的消息机制
55.runtime具体应用
56.runtime如何通过selector找到对应的IMP地址？
57.简述下Objective-C中调用方法的过程
58.load和initialize的区别？
59.怎么理解Objective-C是动态运行时语言？

50-59跳转链接：iOS最新面试题+答案（Runtime篇）
目录：
60.什么情况使用weak关键字，相比assign有什么不同？
61.如何让自己的类用copy修饰符？如何重写带copy关键字的setter？
62.深拷贝与浅拷贝分别是什么？
63.@property的本质是什么？ivar、getter、setter是如何生成并添加到这个类中的？
64.@protocol和category中如何使用@property
65.使用CADisplayLink、NSTimer有什么注意点？BAD_ACCESS在什么情况下出现？
66.iOS内存分区情况
67.iOS内存管理方式
68.循环引用
69.ARC 的 retainCount 怎么存储的？
70.ARC 在编译时做了哪些工作？

60-70跳转链接：iOS最新面试题+答案（Runtime篇）
目录：
71.时间复杂度 / 空间复杂度
72.常用的排序算法有哪些？
73.字符串反转
74.链表反转（头差法）
75.如何查找第一个只出现一次的字符（Hash查找）
76.如何查找两个子视图的共同父视图？
77.无序数组中的中位数(快排思想)
78.如何给定一个整数数组和一个目标值，找出数组中和为目标值的两个数。

71-78跳转链接：iOS最新面试题+答案（算法篇）
目录：
79.数据结构的存储一般常用的有几种？各有什么特点？
80.集合结构 线性结构 树形结构 图形结构
81.单向链表 双向链表 循环链表 分别为什么？
82.数组和链表区别有哪些？
83.堆、栈和队列 分别是什么？
84.输入一棵二叉树的根结点，求该树的深度？
85.输入一课二叉树的根结点，判断该树是不是平衡二叉树？
86.字符匹配 & 字符去重的方法

79-86跳转链接：iOS最新面试题+答案（数据结构篇）


--------题库二-----------
iOS基础
1：讲讲你对atomic & noatomic的理解
原子性访问加不加锁，noatomic属性访问的时候不加锁，高效率，节省开支，

atomic加锁访问，不是绝对的安全，只针对于setter，getter的时候安全，在异步线程，同时访问对象array，可以被篡改添加删除元素

2：属性的实质是什么？
ivar+setter+getter

ivar其实是一个objc_ivar的指针，objc_ivar是一个struct,其中包含变量名、变量类型

3：被 weak 修饰的对象在被释放的时候会发生什么？是如何实现的？知道sideTable 么？里面的结构可以画出来么？
runtime 维护了一个weak表，本质是哈希表(hash)，
key：对象的地址
value：weak指针地址组成的数组
释放时，会调用clearDeallocating函数，通过对象地址也是key的值，找到对应的value数组，进行遍历，清理对象

sidetable

struct SideTable {

// 引用计数表

RefcountMap refcnts;

//弱引用表

weak_table_t weak_table;

...

4：block 用什么修饰？strong 可以？
block的内存地址开辟在栈区，栈区的特点就是创建的对象随时会被销毁掉，一但这个销毁了，再去调用这个对象，就会造成crash，用copy修饰后内存在堆区，不会函数调用完就结束，随对象销毁才销毁，用copy进行修饰，不论传入的对象是否可变，我本身就是一个不可变的副本，如果我们使用是strong,那么这个属性就有可能指向一个可变对象,如果这个可变对象在外部被修改了,那么会影响该属性

5：深拷贝和浅拷贝怎么理解？
浅Copy：可以理解为指针的复制，只是多了一个指向这块内存的指针，共用一块内存

深Copy：理解为内存的复制，两块内存是完全不同的，也就是两个对象指针分别指向不同的内存，互不干涉

6：混编时长优化
由于OC预编译头文件中导入了xxx-Swift.h，该文件包含了Swift中所有类生成的可供OC调用的Swift类，故Swift中任意类增删改查会导致OC预编译头全部重新编译，导致每次编译速度极慢，OC预编译头文件中去除xxx-Swift.h，改为需要混编引用Swift类时，在该文件中导入xxx-Swift.h即可，此举极大地提高了编译速度

7：谈谈你对事件的传递链和响应链的理解
iOS手指触摸(Touch)操作时会将其打包成一个UIEvent对象，hit-test view:事件传递给控件的时候，就会调用该方法，去寻找最合适的view并返回看可以响应的view，

事件的传递方向: 事件传递是从上自下传递，

响应是从下到上，所谓的上就是父视图而已，也就是离窗口最近的

8：谈谈 KVC 以及 KVO 的理解？
KVC简称KeyValueCoding，是一个基于NSKeyValueCoding非正式协议的机制，就是直接通过key值对对象的value进行存取操作

KVO是基于runtime机制实现的，当某个类的属性对象第一次被观察时，系统就会在运行期动态地创建该类的一个派生类，在这个派生类中重写基类中任何被观察属性的setter方法。派生类在被重写的setter方法内实现真正的通知机制，监听变化

9：RunLoop的作用是什么？它的内部工作机制了解么？
保证程序的持续运行，app启动后就会有常驻的runloop，工作的时候工作，休息的时候休息，处理所有事件相关，处理定时器nstimer在cell上滑动暂停的问题，主要因为创建是在defaultMode模式，要切换成UITrackingRunLoopMode

10：苹果是如何实现 autoreleasepool的？
@objc_aotureleasePush objc_aotureleasePop 一个双向联表组成，

通过调用autoreleaseFast函数向自动释放池的链表栈中添加一个对象，不过push函数的入栈的是一个哨兵对象，而autorelease函数入栈的是需要加入autoreleasepool的对象。
那些加入AutoreleasePool中的对象到底延迟到什么时候释放呢？

我觉得应该是在当前runloop迭代结束时释放的，因为系统在每个runloop迭代中都加入了自动释放池push和pop。

11：谈谈你对 (函数响应式) 的理解，延伸一下 RxSwift 或者 RAC
冷信号：(例如网络请求)

是被动的，只有当你订阅的时候，它才会发布消息

只能一对一，当有不同的订阅者，消息是重新完整发送。

热信号：(例如 UI 交互)

是主动的，尽管你并没有订阅事件，但是它会时刻推送，

可以有多个订阅者，是一对多，集合可以与订阅者共享信息。

rxSwift

Subject概念，辅助类型，它们既是 可监听序列（ Observable ）也是 观察者（ Observer）。如果你能合适的应用这些 辅助类型，它们就可以帮助你更准确的描述事物的特征

PublishSubject 将对观察者发送订阅后产生的元素，而在订阅前发出的元素将不会发送给观察者

AsyncSubject 将在源 Observable 产生完成事件后，发出最后一个元素

ReplaySubject 将对观察者发送全部的元素，无论观察者是何时进行订阅的

BehaviorSubject 进行订阅时，它会将源 Observable 中 最新的元素 发送出来（如果不存在最新的元素，就发出默认元素）。然后将随后产生的元素发送出来

ControlProperty 专门用于描述 UI 控件属性的

数据处理

just() of() 可变数量的参数（必需要是同类型的）Observable.of("A", "B", "C")

12：平时开发有没有用过 Instrument？
检测循环引用，启动选择 Allocations 来查看页面跳转过后的 Persistent 个数 是否为0 个数增加则没释放，deinit dealloc 是否执行

13：如何令自己所写的对象具有拷贝功能?
实现nscoping协议
看需要实现的对象是什么样的类型实现不同的方法

(id)copyWithZone:(nullable NSZone *)zone;

(id)mutableCopyWithZone:(nullable NSZone *)zone;

14：通知原理
iOS消息通知机制算是同步的，观察者只要向消息中心注册， 即可接受其他对象发送来的消息，消息发送者和消息接受者两者可以互相一无所知，完全解耦。这种消息通知机制可以应用于任意时间和任何对象，观察者可以有多个，所以消息具有广播的性质，只是需要注意的是，观察者向消息中心注册以后，在不需要接受消息时需要向消息中心注销，属于典型的观察者模式

15：block 内部可以改变一个int值
需要在外部使用__block进行修饰

没有修饰，被block捕获，是值拷贝。 使用__block修饰,会生成一个结构体，复制int的引用地址，达到修改数据的目的。

16：LLDB实时更新数据
：expression更改一个值。开源调试器 (lldb) e (void) 去执行void方法 实时更新

16.1：imageWithName 和 imageWithFilePath区别
：都会在内存中加载，区别name不会随着对象被销毁掉，path会，所以图片小 icon 用name 图片大 用path

17：for循环断点 从第五次开始
条件判断 edit breakpoint i == 5 再执行断点操作

代码的话 就是 continue 1 ～ 5 以后在执行

18：怎么给label的文字添加点击效果
通过富文本形式追加点击 例如yylabel 或者 tap手势 打开交互 追加action

19：怎么写一个连续动画
图片循环，继承 calayer 重写 draw 方法 实现动画

20：放大缩小图片动画
如果不用系统提供的CAKeyframeAnimation 改变transform 只能通过定时器改变frame来实现

21：绘制平行四边形
let bezierPath = UIBezierPath()确定4角

bezierPath.addArc(withCenter: lettTopPoint, radius: leftTopRadius, startAngle: -CGFloat.pi / 2.0 - smallAngle, endAngle: -CGFloat.pi / 2.0, clockwise: true)

22：绘制不规则uiview
根据UIBezierPath路径绘制 建议用图片

23：计算view中subviews中的最小view
遍历subviews中的所有 获取长宽x 和 数组遍历快排 sortedArrayUsingComparator 对比升序排列 通过tag获取

24：category 扩展区别
category 运行时加入 只能添加方法

扩展是 class编译阶段 可以定义私有的方法、属性和实例变量

；25：文件序列化
遵循 encodeWithCoder 写入复杂对象model存储 plist做数据备份 无网展示数据之类

26：观察者模式
就是一个对象拥有多个特征,当某一个特征发生变化时,另外一个对象做出相应的处理和操作.后者观察前者的一举一动,并及时对一些变化做出响应。 kvo 通知

27: 离屏渲染
GPU在当前帧缓冲区以外开辟一个缓冲区进行渲染操作。意为离屏渲染，指的是GPU在当前屏幕缓冲区以外新开辟一个缓冲区进行渲染操作

性能影响

（1）创建新缓冲区

要想进行离屏渲染，首先要创建一个新的缓冲区

（2）上下文切换

离屏渲染的整个过程，需要多次切换上下文环境：先是从当前屏幕（On-Screen）切换到离屏（Off-Screen），等到离屏渲染结束以后，将离屏缓冲区的渲染结果显示到屏幕上有需要将上下文环境从离屏切换到当前屏幕。而上下文环境的切换是要付出很大代价的

iOS 9.0 之前：UIimageView跟UIButton设置圆角都会触发离屏渲染

iOS 9.0 之后：UIImageView里仅图片设置圆角不会触发离屏渲染了。如果设置其他背景、阴影效果之类的还是会触发离屏渲染的。UIbutton仅背景颜色和边框情况下设置圆角不会触发离屏渲染。如果设置其他背景图片、阴影效果之类的还是会触发离屏渲染的

28：_下划线属性访问在block内部会造成循环引用么？
划线访问实例变量实际是通过 self->_nameLabel 来访问的，所以代码会造成强引用

成员变量(私有属性) 默认是 __strong 修饰的，Block内部直接引用 _成员变量，就会造成循环引用

1> 在 Block 外部加上 __weak typeof (self) weakSelf = self;

2> 在 Block 内部必须加上 __strong typeof(weakSelf) strongSelf = weakSelf;

3> 最后，使用 strongSelf->_成员变量 来处理。 注意: 第2步不能少。

29：iOS内存管理机制
iOS的内存管理是通过引用计数机制,每次操作对象都会有相应的操作引用计数.当引用计数等于0,会给对象发送dealloc消息销毁对象，引用计数iOS内的实现是通过引用计数表，引用计数为0的时候

释放时机
如ARC下强指针指向对象，强指针生命周期结束时候对象会被释放；
自动加入自动释放池的对象，自动释放池收到runloop的通知，执行autoreleasepoolPop方法的时候

30：字符串深拷贝
属性修饰符copy不一定代表着深拷贝，碰上数据源为不可变数据则是浅拷贝（指针拷贝），碰上数据源是可变数据则是深拷贝（内容拷贝）； NSObject的方法copy也不一定代表着浅拷贝，碰上数据源为不可变数据则是浅拷贝，碰上数据源是可变数据则是深拷贝； NSObject的方法mutableCopy不管数据源是不可变还是可变，都是深拷贝

NSMutableArray *actionSheetItems = [@[] mutableCopy];

Runtime
1：什么是 isa，isa 的作用是什么？
objc_object中有一个Class类型的属性isa

objc_object中的isa指的是对象的类

objc_class中的isa指的是类的元类

2：load 和 initialize 的区别？
+load

1、只要程序启动就会将所有类的代码加载到内存中（在main函数执行之前）, 放到代码区(无论该类有没有被使用到都会被调用)

2、+load方法会在当前类被加载到内存的时候调用, 有且仅会调用一次

3、当父类和子类都实现+load方法时, 会先调用父类的+load方法, 再调用子类的+load方法

4、先加载原始类，再加载分类的+load方法

5、当子类未实现+load方法时，不会调用父类的+load方法

＋initialize

1、当类第一次被使用的时候就会调用(创建类对象的时候)

2、initialize方法在整个程序的运行过程中只会被调用一次, 无论你使用多少次这个类都只会调用一次

3、initialize用于对某一个类进行一次性的初始化

4、先调用父类的initialize再调用子类的initialize

5、当子类未实现initialize方法时，会把父类的实现继承过来调用一遍，再次之前父类的initialize方法会被优先调用一次

6、当有多个Category都实现了initialize方法，会覆盖类中的方法，只执行一个(会执行Compile Sources 列表中最后一个Category 的initialize方法)

3：_objc_msgForward 函数是做什么的？直接调用会发生什么问题？
当对象没有实现某个方法 ，会调用这个函数进行方法转发。 （某方法对应的IMP没找到，会返回这个函数的IMP去执行）

4：简述下 Objective-C 中调用方法的过程-消息转发
从全局来看，消息转发机制共分为3大步骤：

1.Method resolution 方法解析处理阶段

2.Fast forwarding 快速转发阶段

3.Normal forwarding 常规转发阶段

消息转发分为两个阶段，第一阶段先征询接收者所属的类，看其是否能动态添加方法，这叫做“动态方法解析”。第二阶段涉及“完整的消息转发机制”。如果运行期系统已经把第一阶段执行完了，那么接收者自己就无法再以动态新增方法的手段来响应包含该选择子的消息了。此时运行期系统就会请求接收者以其他手段来处理与消息相关的方法调用。细分为两步：首先，让接收者看看有没有其他对象能处理这条消息。如果有，则运行期系统会把消息转给那个接收者，于是消息转发结束。如果没有这个“备援接收者”，则启动完整的消息转发机制，运行期系统会把与消息有关的全部细节封装到NSInvocation对象中，再给接收者最后一次机会，令其设法解决当前还未处理的这条消息

网络&多线程
1：HTTP的缺陷是什么？
通信使用明文（不加密），内容可能会被窃听，不验证通信方的身份，因此有可能遭遇伪装，无法证明报文的完整性，所以有可能已遭篡改

2：HTTP和HTTPS的区别？
多了一层ssl的协议，https双向的证书验证，非对称加密方式更安全

3：谈谈三次握手，四次挥手！为什么是三次握手，四次挥手？
3次握手连接or4次挥手断开的过程，我觉得这个地方还是需要自我理解，用自己的话去表达出来

4：任务派发方式
w()同步执行，完成了它预定的任务后才返回，阻塞当前线程

dispatch_async()异步执行，会立即返回，预定的任务会完成但不会等它完成，不阻塞当前线程

串行队列，每次只能执行一个任务，并且必须等待前一个执行任务完成

并发队列，一次可以并发执行多个任务，不必等待执行中的任务完成

5：GCD死锁怎么处理？
在GCD中，主要的死锁就是当前串行队列里面同步执行当前串行队列。解决的方法就是将同步的串行队列放到另外一个线程执行

6：线程锁有哪些？
1.NSlock

[lock lock] [lock unlock]

trylock 尝试加锁 已经锁住，返回no

lockbeforedate 方法会在所指定Date之前尝试加锁，如果在指定时间之前都不能加锁 返回no

2.synchronized

@synchronized(self){

NSLog(@"线程1开始");

sleep(10);

NSLog(@"线程1结束");

}

节省代码，自动为对象加入锁，该处理例程会在异常抛出的时候自动的释放互斥锁。所以如果不想让隐式的异常处理例程带来额外的开销，则不推荐使用synchronized

3.GCD信号量

dispatch_semaphore_t semaphore = dispatch_semaphore_create(1);

dispatch_semaphore_wait(semaphore, DISPATCH_TIME_FOREVER);

NSLog(@"线程2");

dispatch_semaphore_signal(semaphore);

7：线程之间的依赖
NSOperation 通过创建

NSOperationQueue *queue = [[NSOperationQueue alloc]init];

[queue addOperation:task1];

[task2 addDependency:task1];

8：怎么在任务1 2 执行完后 在执行3 不用信号量
使用GCD实现：A、B、C三个任务并发，完成后执行任务D？

所有异步任务添加到并发队列中，然后使用dispatch_group_notify函数，来监听前面多个的任务是否完成，如果完成, 就会调用这个方法

dispatch_sync(serial_queue,{//任务}); //同步分配任务到串行队列

dispatch_async(serial_queue,{//任务});//异步分配任务到串行队列

dispatch_sync(concurrent_queue,{//任务});//同步分配任务到并发队列

dispatch_async(concurrent_queue,{//任务});//异步分配任务到并发队列

//创建分组

dispatch_group_t group =dispatch_group_create();

//创建队列

dispatch_queue_t queue =dispatch_queue_create("queue",DISPATCH_QUEUE_CONCURRENT);

//往分组中添加任务

dispatch_group_async(group, queue, ^{

[NSThread sleepForTimeInterval:2];//模拟耗时操作

NSLog(@"11111 %@", [NSThreadcurrentThread]);

});

//往分组中添加任务

dispatch_group_async(group, queue, ^{

[NSThreadsleepForTimeInterval:1];//模拟耗时操作

NSLog(@"2222 %@", [NSThreadcurrentThread]);

});

//分组中任务完成以后通知该block执行

dispatch_group_notify(group, queue, ^{

NSLog(@"完成 %@", [NSThreadcurrentThread]);

dispatch_async(dispatch_get_main_queue(), ^{

NSLog(@"通知主线程刷新UI %@", [NSThreadcurrentThread]);

});

});

数据结构


1：输入一棵二叉树的根结点，求该树的深度？
如果一棵树只有一个结点，它的深度为1。 如果根结点只有左子树而没有右子树， 那么树的深度应该是其左子树的深度加1，同样如果根结点只有右子树而没有左子树，那么树的深度应该是其右子树的深度加1. 如果既有右子树又有左子树， 那该树的深度就是其左、右子树深度的较大值再加1

public static int treeDepth(BinaryTreeNode root) {

if (root == null) {

return 0;

}

int left = treeDepth(root.left);

int right = treeDepth(root.right);

return left > right ? (left + 1) : (right + 1);

}

2：输入一课二叉树的根结点，判断该树是不是平衡二叉树？
如果某二叉树中任意结点的左右子树的深度相差不超过1，那么它就是一棵平衡二叉树，每个节点只需遍历一次进行对比

3：数组和链表的区别？相应插入删除，下标定位的时间复杂度？
内存分配，数组在栈区，链表在堆区。

数组利用下标定位，时间复杂度为O(1)，链表定位元素时间复杂度O(n)；

数组插入或删除元素的时间复杂度O(n)，链表的时间复杂度O(1)。

数组查找方便一些，插入删除链表方便。

算法
1：查找第一个只出现一次的字符（Hash查找）
hash查找之前先把字符类型转成无符号类型，空间换时间，用buffer数组记录当前只找到一次的字符。

2：查找两个子视图的共同父视图
数据结构中的二叉树，查找一个普通二叉树中两个节点最近的公共祖先问题

假设两个视图为UIViewA、UIViewC，其中 UIViewA继承于UIViewB，UIViewB继承于UIViewD，UIViewC也继承于UIViewD；即 A->B->D，C->D

3：求无序数组当中的中位数
(快排思想，选中关键字，高低交替扫描)，

原理：从第1个数开始起，与后面的数字相互比较，满足条件的向后位移（值交换），若不满足条件，拿到大一点的数值继续向后比较

4：给定一个整数数组和一个目标值，找出数组中和为目标值的两个数
你可以假设每个输入只对应一种答案，且同样的元素不能被重复利用。 示例:给定nums = [2, 7, 11, 15], target = 9 --- 返回 [0, 1] 思路：

第一层for循环从索引0到倒数第二个索引拿到每个数组元素，

第二个for循环遍历上一层for循环拿到的元素的后面的所有元素

5：什么是红黑树？
所有节点是红色或黑色。

根节点是黑色。

所有叶子节点都是黑色。

从任一节点到其每个叶子节点的所有路径都包含相同数目的黑色节点。

从每个叶子到根的所有路径上不能有两个连续的红色节点。

6：链表反转
构建一个指定链表 1->3->8->5->4->2，并将其翻转打印

思路：头插法实现链表反转。定义一个新的head指针作为链表的头部指针，定义一个P指针遍历链表，将每次遍历到的元素插入到head指针后。

7：字符串反转
给定字符串 Hello, world, 实现将其反转。输出结果dlrow,olleh。

思路：使用两个指针，一个指向字符串首部begin，一个指向字符串尾部end。遍历过程逐渐交换两个指针指向的字符，结束条件begin大于end。

8：求和
斐波纳契数列求和 f（n） = f（n - 1）+ f（n - 2） 1次就是1。2次就是2 青蛙跳 跳1步 跳2步

【fn】是数段中最末的那个数
【fn-1】是最末之前一位的那个数

架构设计
1：可以说几个重构的技巧么？你觉得重构适合什么时候来做？
重复代码的提炼，冗长方法的分割，嵌套条件分支的优化，去掉一次性的临时变量，消除过长参数列表，提取类或继承体系中的常量，让类提供应该提供的方法，拆分冗长的类，提取继承体系中重复的属性与方法到父类

性能优化
1：谈谈你对离屏渲染的理解？
当我们需要圆角效果时，可以使用一张中间透明图片蒙上去

使用ShadowPath指定layer阴影效果路径

使用异步进行layer渲染（Facebook开源的异步绘制框架AsyncDisplayKit）

设置layer的opaque值为YES，减少复杂图层合成

尽量使用不包含透明（alpha）通道的图片资源

尽量设置layer的大小值为整形值

直接让美工把图片切成圆角进行显示，这是效率最高的一种方案

很多情况下用户上传图片进行显示，可以让服务端处理圆角

使用代码手动生成圆角Image设置到要显示的View上，利用UIBezierPath（CoreGraphics框架）画出来圆角图片

Core Animation工具检测离屏渲染

对于离屏渲染的检测，苹果为我们提供了一个测试工具Core Animation。可以在Xcode->Open Develeper Tools->Instruments中找到

2：tableView 有什么好的性能优化方案？
tableview优化最主要：复用cell，header，footer实例；使用约束布局cell子控件时不多次添加约束；图片不过大，尽量不使用透明视图；避免阻塞主线程；计算高度方法不做大量逻辑处理

cell是否使用了复用机制而不是每一次都创建新的cell

如果每次都创建新的cell，在滑动的时候会表现为：刚开始的时候很顺畅，但是会越来越卡，内存跟着一直升高，停止滑动的时候也不会降下来。使用缓存机制创建的cell，开始滑动的时候内存会开始上升，等创建了一个屏幕再加半屏的cell之后，内存趋于平稳。

cell是否添加了大量的子控件，或者对layer做了过多的操作

如果添加了大量的子控件，使用drawRect方法添加子控件，平衡GPU与CPU的负担。同时还需要注意尽量使用不透明视图和不重叠的渐变，否则会加大GPU的负担，造成性能不佳。

高度计算方法时不做复杂的计算，尽量只使用加减乘除

3：如何降低APP包的大小？
图片压缩，无用代码删除等等

4：启动时间优化
冷启动+load减少无用引入，减少sleep主程的事件，三方库的AppDelegate的初始化等等

swift
1：类(Class)和结构体(Struct)区别
1. 内存管理方式不一样， 类引用类型， 分配在堆上。 结构体值类型，分配在栈上。

2. class可以继承父类，struct不可以继承

3. 结构体构造函数, 会自动生成带参数的构造器。类不会对有初始化赋值的属性, 生成带参数的构造器

2：Codable
4.0后,终于有了Codable可以直接将json转成对象 进行模型数据序列化 ：SwiftyJSON

3：！？
是用来处理值可能缺失的情况，也就是没有值的情况(也就是OC中NULL); 感叹号( ! )就是与之相反的, 就是一定有值(非可选类型)，不存在空值的情况(OC中NULL)

4：什么是逃逸闭包
当闭包作为一个实际参数传递给一个函数时，并且是在函数返回之后调用，我们就说这个闭包逃逸

1、延迟调用

2、作为属性存储，在后面进行调用