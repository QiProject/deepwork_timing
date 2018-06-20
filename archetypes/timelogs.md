---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: "timelog"
layout: "timelog"
csvs_path: "/csvs/2018/%s"
---
