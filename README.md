# Effective-Cpp-Series-Notes
Effective C++, More Effective C++, Effective Modern C++笔记

## Effective C++ |> Content

- 1 **让自己习惯C++**
  - [条款01：视C++为一个语言联邦](EffectiveCpp/Chapter1/01.md)
  - [条款02：尽量以const,enum,inline替换#define](EffectiveCpp/Chapter1/02.md)
  - [条款03：尽可能使用const](/EffectiveCpp/Chapter1/03.md)
  - [条款04：确定对象被使用前已先被初始化](/EffectiveCpp/Chapter1/04.md)
- 2 **构造/析构/赋值运算**
  - [条款05：了解C++默默编写并调用哪些函数](/EffectiveCpp/Chapter2/05.md)
  - [条款06：若不想使用编译器自动生成的函数，就该明确拒绝](/EffectiveCpp/Chapter2/06.md)
  - [条款07：为多态基类声明virtual析构函数](/EffectiveCpp/Chapter2/07.md)
  - [条款08：别让异常逃离析构函数](/EffectiveCpp/Chapter2/08.md)
  - [条款09：绝不在构造和析构过程中调用virtual函数](/EffectiveCpp/Chapter2/09.md)
  - [条款10：令operator=返回一个reference to `*this`](/EffectiveCpp/Chapter2/10.md)
  - [条款11：在operator=中处理“自我赋值”](/EffectiveCpp/Chapter2/11.md)
  - [条款12：复制对象时勿忘其每一个成分](/EffectiveCpp/Chapter2/12.md)
- 3 **资源管理**
  - [条款13：以对象管理资源](/EffectiveCpp/Chapter3/13.md)
  - [条款14：在资源管理类中小心copying行为](/EffectiveCpp/Chapter3/14.md)
  - [条款15：在资源管理类中提供对原始资源的访问](/EffectiveCpp/Chapter3/15.md)
  - [条款16：成对使用new和delete时要采用相同形式](/EffectiveCpp/Chapter3/16.md)
  - [条款17：以独立语句将new对象置入智能指针](/EffectiveCpp/Chapter3/17.md)
- 4 设计与声明
  - [条款18：让接口容易被正确使用，不易被误用](/EffectiveCpp/Chapter4/18.md)
  - [条款19：设计class犹如设计type](/EffectiveCpp/Chapter4/19.md)
  - [条款20：宁以pass-by-reference-to-const替换pass-by-value](/EffectiveCpp/Chapter4/20.md)
  - [条款21：必须返回对象时，别妄想返回其reference](/EffectiveCpp/Chapter4/21.md) 
  - [条款22：将成员变量声明为private](/EffectiveCpp/Chapter4/22.md)
  - [条款23：宁以non-member、non-friend替换member函数](/EffectiveCpp/Chapter4/23.md)
  - [若所有参数皆需类型转换，请为此采用non-member函数](/EffectiveCpp/Chapter4/24.md)
  - [条款25：考虑写一个不抛异常的swap函数](/EffectiveCpp/Chapter4/25.md)
- 5 **实现**
  - [条款26：尽可能延后变量定义式的出现时间](/EffectiveCpp/Chapter5/26.md)
  - [条款27：尽量少做转型操作](/EffectiveCpp/Chapter5/27.md)

## More Effective C++ |> Content

## Effective Modern C++ |> Content