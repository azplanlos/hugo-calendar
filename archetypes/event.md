+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
type = 'event'
start_date = '2026-02-18T12:00:00Z'
+++

# {{ replace .File.ContentBaseName "-" " " | title }}