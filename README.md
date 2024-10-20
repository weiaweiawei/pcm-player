### 网页版播放音频

### 方式：Audio Context

### 介绍

我们可能使用过 Canvas,在绘画的时候，需要找到一个上下文环境，来管理绘画的内容；

同理，处理音频的时候也可以使用这种思想，这就是引入了所说的 `Audio Context`，它是一个管理、播放声音的对象

### 使用
一、创建一个音频上下文
```js
var AudioContext = window.AudioContext || window.webkitAudioContext;
var ctx = new AudioContext();
```

二、播放音频
