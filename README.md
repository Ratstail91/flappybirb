# Flappybirb

This is a working demo of the Toy programming language working in the Unity game engine.

```
import "Unity";

print "Hello birb.toy";

const birb = Unity.Fetch("Birb");

assert(birb != null, "birb is null");

print birb;

birb.Awake = () => {
	print "birb.Awake";
};
```

You can find the [latest build of Toy here](https://github.com/Ratstail91/Toy).