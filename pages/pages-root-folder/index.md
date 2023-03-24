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
  title: "Current Research"
  url: 'http://alfaproject-phb.github.io/research/'
  image: widget-1-302x182.jpg
  text: 'Here you can find informations about our current research project. Get informed and participate'
widget2:
  title: "Our Publications"
  url: 'http://alfaproject-phb.github.io/publication/'
  image: widget-1-302x182.jpg
  text: 'Here you can find a quick and informative overview of our published papers.'
  
widget3:
  title: "Our Blog"
  url: 'http://alfaproject-phb.github.io/blog/'
  image: widget-github-303x182.jpg
  text: 'Here you can find updates on our research or interesting insights into our field and academic work' 

#The code is well-documented and explains you how it works.'
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
  url: https://www.soscisurvey.de/fantasy_2023/
  text: Participate in our study! ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

