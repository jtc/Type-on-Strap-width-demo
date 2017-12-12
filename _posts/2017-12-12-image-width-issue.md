---
layout: post
title: Image Width Issue
---
The below image has been inserted through Markdown and is its native size of 600x600px.
{% raw %}
```markdown
![600x600 Markdown]({{ site.baseurl }}/assets/img/rainbow-color-square-hi.png)
```
{% endraw %}
![600x600 Markdown]({{ site.baseurl }}/assets/img/rainbow-color-square-hi.png)


The below image has been inserted through HTML and is its native size of 600x600px.
{% raw %}
```html
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" alt="600x600 HTML" />
```
{% endraw %}
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" alt="600x600 HTML" />


The below image has been inserted through HTML, but has been resized to 300 in height *only*.
{% raw %}
```html
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" height="300" alt="300x300 HTML" />
```
{% endraw %}
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" height="300" alt="300x300 HTML" />


The below image has been inserted through HTML, but has been resized to 300 in *both* height *and* width.
{% raw %}
```html
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" width="300" height="300" alt="300x300 HTML" />
```
{% endraw %}
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" width="300" height="300" alt="300x300 HTML" />


The below image has been inserted through HTML, but has been resized to 300 in width *only*.
{% raw %}```html
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" width="300" alt="300x300 HTML" />
```
{% endraw %}
<img src="{{ site.baseurl }}/assets/img/rainbow-color-square-hi.png" width="300" alt="300x300 HTML" />