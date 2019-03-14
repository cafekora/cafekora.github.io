---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "About the kora"
  url: '/about-the-kora/'
  image: widget-1-302x182.jpg
  text: 'Read more about what a kora is, where the instrument originally comes from and how one is made.'
widget2:
  title: "Kora Videos"
  url: '/music/videos/'
  text: 'YouTube has lots of great kora videos. See our curated list of the very best. Or click on the image above to watch the current featured track.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://img.youtube.com/vi/U8P9aQ0Phlo/0.jpg" width="244" height="182" alt=""/></a>'
widget3:
  title: "Kora News"
  url: '/blog/'
  image: widget-3-302x182.jpg
  text: 'Read the latest updates on concerts, tours, album releases, workshops, festivals and changes to this site.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/thekoracafe
  text: If you would like to receive (very) occasional emails with site news, click here ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/U8P9aQ0Phlo" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
