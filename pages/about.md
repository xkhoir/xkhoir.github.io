---
layout: page
title: About
permalink: /about/
weight: 3
---



<p align="center">
  <a href="{{ site.baseurl }}">
    <img src="{{ site.author.image }}" alt="{{ site.title }}" width="168px" height="168px" style="display:flex;">
  </a>
<br>
</p>


<p align="center">
Hi Saya **{{ site.author.name }}** :wave:,<br>
Saya merupakan lulusan Sarjana Sistem Informasi dari Institut Teknologi Adhi Tama Surabaya dengan IPK 3.52 dengan predikat memuaskan.

Saya memiliki pengalaman kerja di beberapa perusahaan start up sampai dengan perusahaan besar. Ketertarikan serta minat yang sangat besar saat ini untuk saya dapat bergabung memberikan kinerja terbaik saya di bidang Teknologi Informasi yang sesuai dengan latar belakang pendidikan.

Jika tertarik, silahkan bisa menghubungi saya melalui untuk mendapatkan lampiran CV saya. Terimakasih atas perhatiannya.
</p>


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Editing Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>