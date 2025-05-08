# ch1

## things I didn't know

there are process level caches that are maintained for every core of the CPU. if you use locking strategy (the old way java did concurrency) then you have to synchronize the threads which makes the cache coherency process slower. I'm not sure what this means, so I looked it up. it is called cache coherency protocol inter core communication and there are different implementations of it. the idea basdically is to have the faster memory afforded by these caches available by having a way to keep the data in these caches consistent. I guess forcing the synchronization means waiting a little while for them all to catch up even if one core is not going to be needed right away and doesn't need the latest information.

behavior parameterization. I forgot about this term it is a good one. high level is now you can pass a function to another function and you can therefore instead of having two similar functions pass jus the parts of functions that are different to a common function. this is a lot of the appeal of functional programming to me, the ability to make truly modular code.
