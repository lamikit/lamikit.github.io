---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="text-align: right; margin-bottom: 20px;">
  <a href="https://lamikit.github.io" style="color: #2c3e50; text-decoration: none; font-weight: bold;">🌐 Online Portfolio: https://lamikit.github.io</a>
</div>

## 🎓 Education
* **M.S. in Electronic Engineering**, Shanghai Jiao Tong University (SJTU), 2021 – 2024
  * *GPA: 3.4/4.0*
* **B.S. in Mechatronic Engineering**, Beijing Institute of Technology (BIT), 2017 – 2021
  * *GPA: 3.3/4.0*

## 💼 Research & Work Experience
**Fibre Laser Design Engineer** | China Academy of Engineering Physics (CAEP) | *May 2024 – Apr 2025*

## 🏆 Selected Honors & Awards
* **National Scholarship** , 2023 – 2024
* **Outstanding Graduate** of Shanghai Jiao Tong University, 2023 – 2024
* **Distinguished Student Paper Award**, ICDT, 2022 – 2023
* **Merit Student** of SJTU, 2023 – 2024
* **Faw and Toyota Scholarship**, BIT, 2018 – 2019

## 📚 Publications (Journal & Conference)
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## 💡 Patents
1. **Lu J, Chen Q.** A phase modulation method, system, device, and medium for a liquid crystal lens array. (*CN202310323011.2*)
2. **Lu J, Chen Q, Tang M, Ding W, Sun C.** A field phase modulation method, system, and device for micro/nano scale liquid crystal devices. (*CN202311413087.0*)
3. **Sun C, Lu J, Tang M, Zhang Y, Ding W, Chen Q, Yang J.** A templated polymer-stabilized CLC energy-saving window device. (*CN202310574707.2*)

## 🎤 Talks & Presentations
{% for post in site.talks reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## 🏫 Teaching Experience
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## 🛠️ Skills
* **Programming:** Python (Deep Learning), C, Matlab.
* **Specialized Software:** Lighttools, Dimos.2d, TechWiz LCD 3d, Virtual Lab, Solidworks, AutoCAD, Lumerical FDTD.
* **Languages:** English (IELTS 6.5), Mandarin (Native).
