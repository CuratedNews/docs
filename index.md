---
title: Home
layout: home
nav_order: 1
description: "Curated News & Curated News Business documentation gives Curated News users, employees, and clients that ability to find technical information about our services."
permalink: /
---

# Let's get you up to speed
{: .fs-9 }

We want users to have technical explanations on how our services work and operate.
{: .fs-6 .fw-300 }

[Learn more](#learn-more){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View it on GitHub](https://github.com/curatednews/docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

{: .warning }
> This website is currently under development.

## Learn more

Welcome to the [Curated News](https://curatednews.xyz) and [Curated News Business](https://curatednewsbusiness.xyz) documentation and wiki page. We host it on [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages) to adhere to our Curated Healthy program, which increases our commitment to fostering and developing a healthy ecosystem where transparency is paramount. Users, employees, and clients can see what we've said and when we've said it directly from our public documentation repository on [GitHub](https://github.com/curatednews/docs).

### Contributing

Only authorized employees are allowed to contribute to the creation of our docs. If you find an error, please send us a pull request and detail the issue you are trying to fix. If you do not find a technical doc that you think should be available for public consumption, please contact us using the [contact form](https://curatednews.xyz/curatedcontact) on our website.

#### Thank you docs contributors! 

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>
