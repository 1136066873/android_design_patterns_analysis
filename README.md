# Android源码设计模式分析开源项目

## 简述
该项目通过分析Android系统中的设计模式来提升大家对设计模式的理解，从源码的角度来剖析既增加了对Android系统本身的了解，也从优秀的设计中领悟模式的实际运用以及它适用的场景，避免在实际开发中的生搬硬套。如果你对面向对象的六大开发原则还不太熟悉，那么在学习模式之前先学习一下[面向对象的六大原则](oop-principles/oop-principles.md)是非常有必要的。       

每一个模式可能在Android源码中有很多个实现，因此我们为每个模式创建一个文件夹，文件夹中为分析这个模式的markdown文件，该文件的命名规则为: 模式名-分析者.md, 例如: adapter-mr.simple.md。我们的原则是通过分析这些源码不仅要学会设计模式本身，而且要通过学习该模式深入到Android源码层的实现，这样不仅学了设计模式，也增加了我们对于Android源码的了解。



## 编写步骤
请移步[Android源码设计模式分析开源项目开发版](https://github.com/simple-android-framework-exchange/android_design_patterns_analysis)。
 

## 模式与文件夹对应列表
| 模式名        | 文件夹           |
| ------------- |:-------------:| 
|    适配器模式    |  [adapter](adapter)			|  
|    抽象工厂模式  |   [abstract-factory](abstract-factory) |    
| 	 桥接模式	     |    [bridge](bridge)	 		|    
|    Builder模式 |   		[builder](builder)	|  
|    责任链模式   |   [chain-of-responsibility](chain-of-responsibility) |    
| 	 命令模式	    |     [command](command)		 | 
|    组合模式    |  	[composite](composite)		|  
|    装饰模式  	|   [decorator](decorator)	 	|    
| 	 外观模式	     |      [facade](facade)		| 
|    工厂方法模式  |  [factory-method](factory-method) |  
|    享元模式  	 |    [flyweight](flyweight)	|    
| 	 解释器模式	 |  [interpreter](interpreter) | 
|    迭代器模式    |  [iterator](iterator)		|  
|    中介者模式   |    [mediator](mediator)		|    
| 	 备忘录模式	 |   [memento](memento)	  		| 
|    观察者模式   |  [observer](observer)		|  
|    原型模式  	|   [prototype](prototype)	 	|    
| 	 代理模式	    |     [proxy](proxy)			| 
|    单例模式    |  [singleton](singleton)		|  
|    状态模式  	|    [state](state)				|    
| 	 策略模式	     |     [strategy](strategy)	 	| 
|    模板方法模式  |   [template-method](template-method) |    
| 	 访问者模式	 |     [visitor](visitor)	 	| 
