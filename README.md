# WebChimera.js Player Demo

#### Description

Demo for [wcjs-player](https://github.com/jaruba/wcjs-player) showing WebChimera.js Player playing a single video. ``wcjs-player`` uses [WebChimera.js](https://github.com/RSATom/WebChimera.js) to draw the frames of libVLC to a canvas.

#### Demo Install

```
git clone https://github.com/jaruba/node-vlcPlayer-demo.git
cd node-vlcPlayer-demo
```

**Windows**
```
set WCJS_RUNTIME=electron
set WCJS_RUNTIME_VERSION=v0.37.6
set WCJS_VERSION=0.2.5
set WCJS_ARCH=ia32
```

**OSX/Linux**
```
export WCJS_RUNTIME="electron"
export WCJS_RUNTIME_VERSION="v0.37.6"
export WCJS_VERSION="0.2.5"
export WCJS_ARCH="ia32"
```

```
npm install
```

Now download Electron v0.37.6 for 32bit and run `app.js`

!! You can change the configuration values for `wcjs-prebuilt` according to your case, but keep in mind that the options are limited to the [prebuilt packages](https://github.com/RSATom/WebChimera.js/releases)

#### Screenshots

WebChimera.js Player running on NW.js (Windows)

<img src="http://webchimera.org/samples/wcjs-player.png">

WebChimera.js Player running on Electron (Mac)

<img src="http://webchimera.org/samples/wcjs-player-2.png">
