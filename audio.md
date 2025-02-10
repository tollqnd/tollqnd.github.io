---
layout: splash
title: Audio Projects
permalink: /audio/
header:
  # overlay_color: "#252a34"
  overlay_image: assets/images/audio/header.png
  overlay_filter: linear-gradient(rgba(0, 0, 0, 0.0), rgba(33, 33, 33, 1))
feature_row:
  - image_path: /assets/images/audio/generative_radiation.png
    title: "Turning Radiation into Music"
    excerpt: "Using a Geiger counter, a Raspberry Pi and a host computer and DAW (Digital Audio Workstation), I created ambient generative music that played in real-time.
		<br> <br> The Raspberry Pi contained some code that would read its GPIO pins (where the Geiger counter was connected to) and send a packet to another computer on the same network. This computer would then generate a random MIDI note from a selection for each packet, and send it to FL Studio via a virtual MIDI cable for driving audio plugins.
		<br> <br> The audio file here contains 20 minutes of arbitrarily-recorded audio."
    sc_link: "https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/2020768049%3Fsecret_token%3Ds-iE4pbQhFO0h&color=%23ff5500&auto_play=false&hide_related=true&show_comments=false&show_user=false&show_reposts=false&show_teaser=false"
feature_row2:
  - image_path: /assets/images/audio/water_track.png
    title: "A Track Made from Entirely Field Recordings"
    excerpt: "I obtained numerous recordings of water and used my skills in sound design and sample manipulation to create a cohesive, melodic track.
	  <br> <br> Yes, everything you can hear here is a sample of water I recorded, such as rain, dripping, streams, waterfalls and ocean waves."
    sc_link: "https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/2030992012%3Fsecret_token%3Ds-scXKJ1a6gaQ&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"
feature_row3:
  - title: "Random Glitch and Audiovisual Composition"
    excerpt: "A track inspired by glitch music and Ryoji Ikeda. 'Technological' sounds like sine tones and clicks were used in combination with a system I made in FL Studio that would apply various glitch effects according to randomly-generated MIDI. Visuals were added that were synced automatically to these effects using ZGameEditor Visualizer."
    youtube_link: "https://www.youtube.com/embed/O3BAHHHX9IU?si=XhEXovafXMkEGgoD"
feature_row4:
  - title: "Rescore of Sons of the Forest Trailer"
    excerpt: "This first attempt at (re)scoring consisted of both creating new music for the trailer and adding new gameplay sound effects. The latter are mostly well-edited and well-placed royalty-free sound effects but there are a few of my own recordings in there too.
	  <br> <br> The main focus, and what I'm most pleased with, is the music, which I think fits the trailer far better than the original music which is more synthwave-styled."
    youtube_link: "https://www.youtube.com/embed/mbm5gqHIZlU"
---
I've been creating audio, mainly music, since I started messing around with FL Studio aged 13 or so. My self-taught skills were enough to study Electronic Music Production at university and my creativity and capability of making innovative compositions has only increased since then.
<hr style="margin-bottom: 2em">
{% include image_feature_row type="left" %} 
{% include image_feature_row id="feature_row2" type="left" %}
{% include video_feature_row id="feature_row3" type="left" %}
{% include video_feature_row id="feature_row4" type="left" %}