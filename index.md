---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: Tom J. Holland
header:
  overlay_image: assets/images/home_header.jpg
  overlay_filter: rgba(33, 33, 33, 0.6)
# excerpt: 'Musician, Level Designer and Programmer'
feature_row_categories:
  - image_path: /assets/images/audio.png
    title: "Audio"
    url: "/audio/"
  - image_path: /assets/images/level_design.jpg
    title: "Level Design"
    url: "/level-design/"
  - image_path: /assets/images/mods.png
    title: "Mods"
    url: "https://www.curseforge.com/members/f1ashfyre/projects"
    new_tab: true
feature_row_paper:
  - image_path: /assets/images/honours_project_games.jpg
    title: "The Influence of Music on Immersion in Exploratory Video Games"
    excerpt: "A 10,000-word paper I wrote for my Electronic Music Production degree consisting of a literature review, case studies of game music, a study of players, followed by analysis and a conclusion."
    url: "/assets/pdf/TH_Honours_Project_The_Influence_of_Music_on_Immersion_in_Exploration-oriented_Video_Games.pdf"
    new_tab: true
    btn_label: "View"
    btn_class: "btn--inverse"
    image_caption: "The games analysed in the paper are Noita (2019), Minecraft (2011), Rust (2013), Terraria (2011) and The Elder Scrolls V: Skyrim (2011)"
---

{% include image_feature_row_2 id="feature_row_categories" %}
{% include better_feature_row type="right" id="feature_row_paper" %}