---
layout: nil
---

{% highlight ruby %}
# Ruby mengerti apa yang
# Anda maksud, bahkan ketika
# Anda ingin melakukan
# matematika pada seluruh
# Array
cities  = %w[ London
              Oslo
              Paris
              Amsterdam
              Berlin ]
visited = %w[Berlin Oslo]

puts "Saya masih perlu " +
     "mengunjungi " +
     "kota-kota berikut:",
     cities - visited
{% endhighlight %}
