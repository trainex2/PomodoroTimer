# PomodoroTimer

1. Put your .mp3 file in music folder
2. Replace `*` with .mp3 name in `script.js`

```javascript
var sessionOverMusic = new Howl({
  //edit this to the music you want to play

  src: ["./music/*.mp3"],
  onend: function () {
    stopMusicButton.prop("disabled", true);
  },
});

var breakOverMusic = new Howl({
  //edit this to the music you want to play
  src: ["./music/*.mp3"],
  onend: function () {
    stopMusicButton.disabled = true;
  },
});
```
