### Example 0
[permalink](#example-0)

{% highlight clojure %}
{% raw %}
user=> (vec (range 10))
[0 1 2 3 4 5 6 7 8 9]

user=> (rseq (vec (range 10)))
(9 8 7 6 5 4 3 2 1 0)
{% endraw %}
{% endhighlight %}

