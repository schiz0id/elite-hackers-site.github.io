---
layout: page-no-ad
weight: 3
title: "Hacking Books"
menu-title: "Books"
permalink: /books/
summary: "<strong>Warning: The books listed here are hard to find in bookstores because of the methods and techniques they cover.</strong> I have read these books to grow my skills and I recommend that you read them as well. Each book talks about a different way of hacking the servers, networks, or computers of your victims."
---
{% assign books = site.books %}
<div class="books">
{% for book in books %}
  {% include ad-amazon.html asin=book.asin title=book.title description=book.description img=book.imgur-sm %}
{% endfor %}
