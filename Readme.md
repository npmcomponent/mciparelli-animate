*This repository is a mirror of the [component](http://component.io) module [mciparelli/animate](http://github.com/mciparelli/animate). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/mciparelli-animate`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# animate

  component for handling CSS3 animations easily with Javascript

## Installation

    $ component install mciparelli/animate

## example

```js
	var Animate = require('animate');
	var animate = Animate('p');
	animate
	.set('bg-keyframe', '3s')
	.start();
	animate.on('animationEnd', function startANewOne(){
		animate
		.set('fg-keyframe', '5s infinite alternate')
		.start();
	});
```

## License

  MIT
