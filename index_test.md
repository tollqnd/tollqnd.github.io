---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: Tom J. Holland
header:
  overlay_image: assets/images/home_header.png
  overlay_filter: linear-gradient(rgba(0, 0, 0, 0.0), rgba(33, 33, 33, 1))
excerpt: 'BA (Hons) in Electronic Music Production'
feature_row_experimental:
  - image_path: /assets/images/audio/generative_radiation.png
    title: "Turning Radiation into Music"
    excerpt: "I used a Raspberry Pi, a Geiger counter and Max to make real-time generative music from ionising radioactive decay."
    url: "/audio/"
  - title: "Glitch Audiovisual Composition"
    excerpt: "A track with synced visuals inspired by glitch music and Ryoji Ikeda, powered by random MIDI triggering different audio effects."
    youtube_link: "https://www.youtube.com/embed/O3BAHHHX9IU?si=XhEXovafXMkEGgoD"
  - image_path: /assets/images/audio.png
    title: "Lorem Ipsum"
    excerpt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vel egestas nibh, sit amet blandit erat."
  - image_path: /assets/images/audio.png
    title: "Lorem Ipsum"
    excerpt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vel egestas nibh, sit amet blandit erat."
feature_row_game_audio:
  - image_path: /assets/images/honours_project_games.jpg
    title: "Music in Exploration Games"
    excerpt: "The Influence of Music on Immersion in Exploratory Video Games: A 10,000-word paper I wrote for my degree featuring case studies and a survey from real players."
    url: "/assets/pdf/TH_Honours_Project_The_Influence_of_Music_on_Immersion_in_Exploration-oriented_Video_Games.pdf"
    new_tab: true
  - title: "Sons of the Forest Trailer Rescore"
    excerpt: "I rescored Sons of the Forest Trailer 3 with the aim of better representing the game's desolate and eerie themes."
    youtube_link: "https://www.youtube.com/embed/mbm5gqHIZlU"
feature_row_sound_design:
  - image_path: /assets/images/audio/water_track.png
    title: "A Track Made of Water"
    excerpt: "A drum and bass/drumstep track I made solely out of processed field recordings of water."
    url: "https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/2030992012%3Fsecret_token%3Ds-scXKJ1a6gaQ&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"
feature_row_other_projects:
  - image_path: /assets/images/level_design.jpg
    title: "Level Design"
    url: "/level-design/"
  - image_path: /assets/images/mods.png
    title: "CurseForge Mods"
    excerpt: "test"
    url: "https://www.curseforge.com/members/f1ashfyre/projects"
    new_tab: true
---

# Experimental
{% include media_feature_row id="feature_row_experimental" %}

# Game
{% include media_feature_row id="feature_row_game_audio" %}

# Sound Design
{% include media_feature_row id="feature_row_sound_design" %}

# Other Projects
{% include image_feature_row_2 id="feature_row_other_projects" %}