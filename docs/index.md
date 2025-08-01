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
  - title: Join the online forum
    excerpt: A place to connect, ask question and share resources.
    image_path: /assets/images/image_forum.png
    url: "https://forum.escs-community.org/"
    btn_label: "Check it out"
    btn_class: "btn--primary"

feature_row2:
  - title: Sign up to the newsletter
    excerpt: The easiest way to be kept updated on what is going on in the ESCS community. We send out a monthly digest of the latest news and developments in the sustainable computing space.
    image_path: /assets/images/image_email.png
    url: "https://zcmp.eu/oRye"
    btn_label: "Subscribe"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row1" type="right" %}
