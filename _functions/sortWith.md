---
title: sortWith
layout: function
permalink: /sortWith
---

# `sortWith`

~~~ scala
trait Collection[A] {
  def sortWith(lt: (A, A) => Boolean): Collection[A]
}
~~~

`sorted` creates a collection with the elements sorted by using a comparison function `lt` which should returns `true` when its first argument is less than the second and `false` otherwise.

<figure class="diagram">
  <img src="images/sortWith.svg" alt="sortWith function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>