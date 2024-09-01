---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

### 대형 언어 모델을 활용한 퓨샷 추론 문제의 데이터 증강
* **Authors**: Wongyu Seo, Woochang Sim, Sundong Kim
* **Link**: [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11705093)

### Reasoning Abilities of Large Language Models: In-Depth Analysis on the Abstraction and Reasoning Corpus
* **Authors**: Seungpil Lee, Woochang Sim, Donghyeon Shin, Sanha Hwang, Wongyu Seo, Jiwon Park, Seokki Lee, Sejin Kim, Sundong Kim
* **Link**: [arXiv](https://arxiv.org/abs/2403.11793)
