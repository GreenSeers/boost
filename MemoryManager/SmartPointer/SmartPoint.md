# SMartPoint-智能指针
-----------------------------------------------
boost库中包含三个非常重要的智能指针，分别是:
- boost::shared_ptr
- boost::weak_ptr
- boost::scoped_ptr

这三个指针的强大有效，已经在C++11中引入了这三个智能指针，分别对应：
- std::shared_ptr
- std::weak_ptr
- std::unique_ptr

下面分别讲讲这三个指针的,具体内容有
- 为什么会有智能指针
- 应用场景
- 多线程下智能指针的应用
- 总结
