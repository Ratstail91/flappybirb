# Flappybirb

This is a working demo of the Toy programming language working in the Unity game engine.

[![Flappy Birb](https://i.gyazo.com/007563fd276bf61e97507d7b561fea49.gif)](https://gyazo.com/007563fd276bf61e97507d7b561fea49)

```
import "Unity";

this.Behaviour.Update = () => {
	if (Unity.GetButtonDown("Fire1")) {
		this.Rigidbody2D.AddForce(0, 10, "impulse");
	}
};

this.Behaviour.FixedUpdate = () => {
	this.Rigidbody2D.Rotation += 1;
};
```

You can find the [latest build of Toy here](https://github.com/Ratstail91/Toy).