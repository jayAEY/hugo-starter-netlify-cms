---
title: Hello website is sum
date: 2023-11-02T20:28:42.375Z
image: dog.jpg
---
<!--StartFragment-->

<header class="site-header">

  <nav class="site-nav">

    <a class="logo" href="/">

      {{ .Site.Title }}

    </a>

    <ul class="main-menu">

      {{ range.Site.Menus.main }}

      <li>

        <a href="{{ .URL }}">{{ .Name }}</a>

      </li>

      {{ end }}

    </ul>

  </nav>

</header>



<!--EndFragment-->