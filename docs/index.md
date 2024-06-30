---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash

title: About the ESCS community
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/nature_2.jpg
excerpt: "This is still a work in progress! But you can already find below links to the main resources so far for the ESCS Community."


feature_row1:
  - title: The online forum
    excerpt: A place to connect, ask question and share resources.
    image_path: /assets/images/image_forum.png
    url: "https://forum.escs-community.org/"
    btn_label: "Check it out"
    btn_class: "btn--primary"

feature_row2:
  - title: The newsletter
    excerpt: The easiest way to be kept updated on what is going on in the ESCS community.
    image_path: /assets/images/image_email.png
    url: "https://zcmp.eu/oRye"
    btn_label: "Subscribe"
    btn_class: "btn--primary"

feature_row3:
  - title: Regular virtual meet-ups
    excerpt: We are working on this, sign up to the mailing list to hear about our progress!  
    image_path: /assets/images/image_meetings.png
---

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row3" type="left" %}
