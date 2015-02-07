---
title: 一句话表达设计模式
date: '2015-01-16'
description:
categories: 'java'
---

[观察者模式](http://ifeve.com/java-example-of-observer-pattern/)：分订阅者、发布者，发布者发布消息给多个订阅者 

[策略模式](http://ifeve.com/java-example-of-strategy-pattern/)：只有运行时才知道会走哪个策略。if-else也能实现，建议将策略抽象出一个接口，运行时决定走哪个实现。  
[状态模式](http://ifeve.com/state-design-pattern-in-java-example-tutorial/)：将一段逻辑委托给另一个对象处理，但是在代码编写时就确定走哪个对象处理，建议抽象一个接口。  

[模板模式](http://ifeve.com/template-method-design-pattern/)：定义做一件事情的步骤，但不具体实现。一般在父类定义做一件事情需要调用哪几个步骤。  
[装饰者模式](http://ifeve.com/java-example-of-decorator-pattern/)：因为多个因素构成了一个类，这些因素自由组合时个数比较多，需要将其中一部分因素抽出来作为一个类，抽出来的类和原来的类组合构成一个综合类。典型例子java IO库。  
  
[备忘录模式](http://ifeve.com/memento-design-pattern-in-java-example-tutorial/)：  
