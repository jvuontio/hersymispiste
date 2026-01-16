+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
showDate = false
showAuthor = false
showPagination = false
draft = false
showComments = false
showWordCount = false
showReadingTime = false
heroStyle = "background"
featureimage = "img/FSM_logo.png"
showHero = true
[_build]
  list = 'never'
+++