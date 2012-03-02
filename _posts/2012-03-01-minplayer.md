---
layout: post
title: "minPlayer"
minplayer:
  debug: true
  template: default
tagline:
category:
tags: []
---

###Check out travist's minPlayer
{% highlight html %}
<script type="text/javascript">
  $(function() {
    console.log('here');
    $("#vimeo").minplayer();
  });
</script>
<video id="vimeo" src="http://vimeo.com/5606758"></video>
{% endhighlight %}
<script type="text/javascript">
  $(function() {
    console.log('here');
    $("#vimeo").minplayer();
  });
</script>
<div style="height:400px;">
  <video id="vimeo" src="http://vimeo.com/5606758"></video>
</div>