# videojs-straas-live-playback-control



## Table of Contents

<!-- START doctoc -->
<!-- END doctoc -->
## Installation

```sh
npm install --save videojs-straas-live-playback-control
```

## Usage

To include videojs-straas-live-playback-control on your website or web application, use any of the following methods.

### `<script>` Tag

This is the simplest case. Get the script in whatever way you prefer and include the plugin _after_ you include [video.js][videojs], so that the `videojs` global is available.

```html
<script src="//path/to/video.min.js"></script>
<script src="//path/to/videojs-straas-live-playback-control.min.js"></script>
<script>
  var player = videojs('my-video');

  player.straasLivePlaybackControl();
</script>
```

### Browserify/CommonJS

When using with Browserify, install videojs-straas-live-playback-control via npm and `require` the plugin as you would any other module.

```js
var videojs = require('video.js');

// The actual plugin function is exported by this module, but it is also
// attached to the `Player.prototype`; so, there is no need to assign it
// to a variable.
require('videojs-straas-live-playback-control');

var player = videojs('my-video');

player.straasLivePlaybackControl();
```

### RequireJS/AMD

When using with RequireJS (or another AMD library), get the script in whatever way you prefer and `require` the plugin as you normally would:

```js
require(['video.js', 'videojs-straas-live-playback-control'], function(videojs) {
  var player = videojs('my-video');

  player.straasLivePlaybackControl();
});
```

## License

MIT. Copyright (c) Kiwi Liu &lt;kiwi71728@icloud.com&gt;


[videojs]: http://videojs.com/
