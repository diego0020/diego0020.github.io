---
layout: "post"
title: A test post 
---
#Mamamia

here we go again
lalalalala

how can I resist

## Some code in fenced markdown

```c
int i;
int r = 0;
for (i=0;i <= 10; i++){
	r += i;
}
cout << r
```

```python
r = 0
for i in xrange(10):
	r += i
print r
```

## the same code with liquid tags

{% highlight c %}
int i;
int r = 0;
for (i=0;i <= 10; i++){
	r += i;
}
cout << r
{% endhighlight %}

{% highlight python %}
r = 0
for i in xrange(10):
	r += i
print r
{% endhighlight %}