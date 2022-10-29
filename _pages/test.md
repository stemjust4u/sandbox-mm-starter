---
permalink: /test/
title: "Test page"
layout: single
---

This is a test page

<button id="myBtn">Try it</button>

{% include snippet.html %}

{% assign my_variable = "tomato" %}
{{ my_variable }}

{% highlight python linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}