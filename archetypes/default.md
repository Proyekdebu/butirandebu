+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
updated = {{ .Date }}
draft = true

image = "images/blog/{{ .BaseFileName }}.jpg"
feature_image = "images/blog/{{ .BaseFileName }}-details.jpg"

+++
