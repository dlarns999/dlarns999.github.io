---
layout: home
author_profile: true
title: ""
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/main.jpg  # 없으면 이 줄 전체 삭제
  actions:
    - label: "GitHub"
      url: "https://github.com/username"
excerpt: "개발과 공부를 기록하는 개인 블로그입니다."
---

## 👋 Welcome!

안녕하세요!  
이곳은 **Jekyll + GitHub Pages**로 만든 개인 블로그입니다.

주로 아래와 같은 내용을 기록합니다:

- 💻 개발 공부 기록
- 🧠 개념 정리 & 회고
- 🛠 프로젝트 정리
- ✍️ 개인 메모

---

## 📝 최근 글

아래는 최근에 작성한 글들입니다.  
관심 있는 주제가 있다면 편하게 읽어보세요 😊

{% raw %}{% for post in site.posts limit:5 %}{% endraw %}
- [{{ post.title }}]({{ post.url }})
{% raw %}{% endfor %}{% endraw %}

---

## 📂 카테고리

{% raw %}{% assign categories = site.categories %}{% endraw %}
{% raw %}{% for category in categories %}{% endfor %}{% endraw %}
- **{{ category[0] }}** ({{ category[1].size }})

---

## 🔗 Links

- GitHub: https://github.com/username
- Email: your@email.com

---

> ✨ 이 블로그는  
> **Minimal Mistakes 테마**와  
> **GitHub Pages**로 운영되고 있습니다.
