Singleton
=========

Turn classes into singletons by implementing the `Singleton` interface.

```haxe
class MyClass implements Singleton {
	public var variable:Float;
}
```

Now you can access `MyClass.instance` from anywhere!

```haxe
MyClass.instance.variable = 4;
```

