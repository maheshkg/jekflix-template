---
layout: page
permalink: /privacy/
title: Privacy Policies
---
<img class="img-rounded" src="/assets/img/uploads/profile.png" alt="Thiago Rossener" width="200">
# mahesh

asdasdasasdas das dasdas dasd 
s
ad asd as

<ul>
  {% for post in site.posts %}
    <li>
      <a  href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
       {% if post.optimized_image %}
          <img src="{{ post.optimized_image }}" width="100%" data-url="{{ post.optimized_image }}" class="preload">
          <noscript>
              <img src="{{ post.optimized_image }}" width="100%">
          </noscript>
      {% elsif post.image %}
          <img src="{{ post.image }}" width="100%" data-url="{{ post.image }}" class="preload">
          <noscript>
              <img src="{{ post.image }}" width="100%">
          </noscript>
      {% else %}
          <img src="/assets/img/placeholder.png" width="100%" data-url="/assets/img/off.jpg" class="preload">
          <noscript>
              <img src="/assets/img/off.jpg" width="100%">
          </noscript>
      {% endif %}
    </li>
  {% endfor %}
</ul>

<table>
<tr>
<td>
Hello Mahesh
</td>
<td>
Hello Mahesh
</td>
</tr>
</table>

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>