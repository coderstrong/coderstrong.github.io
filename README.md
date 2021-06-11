# coderstrong.github.io

[I'm an inline-style link](https://vjs.zencdn.net/7.11.4/video-js.css)

#Demo webm
...
    <video style="width:100%" controls>
    <source src="RecordRTC-2021511-durn2vwuw23.webm" type="video/webm;codecs=vp8">
    Your browser does not support the video tag.
    </video>
...
#Demo mp4
...
    <video style="width:100%" controls>
    <source src="RecordRTC-2021511-bvedflinmhh.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>
...


<link href="https://vjs.zencdn.net/7.11.4/video-js.css" rel="stylesheet" />

<!-- If you'd like to support IE8 (for Video.js versions prior to v7) -->
<!-- <script src="https://vjs.zencdn.net/ie8/1.1.2/videojs-ie8.min.js"></script> -->


<body>
  <video
    id="my-video"
    class="video-js"
    controls
    preload="auto"
    width="640"
    height="264"
    poster="MY_VIDEO_POSTER.jpg"
    data-setup="{}"
  >
    <source src="RecordRTC-2021511-bvedflinmhh.mp4" type="video/mp4">
    <source src="RecordRTC-2021511-durn2vwuw23.webm" type="video/webm;codecs=vp8">
    <p class="vjs-no-js">
      To view this video please enable JavaScript, and consider upgrading to a
      web browser that
      <a href="https://videojs.com/html5-video-support/" target="_blank"
        >supports HTML5 video</a
      >
    </p>
  </video>

  <script src="https://vjs.zencdn.net/7.11.4/video.min.js"></script>
</body>
...