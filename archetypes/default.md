+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++

<!-- Example YouTube embeds: -->
<!-- {{< youtube "VIDEO_ID" >}} -->
<!-- {{< youtube "VIDEO_ID" privacy=true >}} -->
<!-- {{< youtube "VIDEO_ID" start=30 title="Custom Title" >}} -->
