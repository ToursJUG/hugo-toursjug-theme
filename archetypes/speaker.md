---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
# description: "" # Description courte du speaker si besoin
date: {{ .Date }} # date d'ajout du speaker
link: "{{ lower (replace (replace (replace (replace .TranslationBaseName "-" "") "é" "e") "è" "e") "ç" "c") }}"
---