+++
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
updated = {{ .Date }}
featured = false

thumbnail = "images/blog/{{ .BaseFileName }}/{{ .BaseFileName."
featureImage = "images/blog/{{ .BaseFileName }}/{{ .BaseFileName }}-detail."

+++
