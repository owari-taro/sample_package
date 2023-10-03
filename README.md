# sample_package
create my first sample python package


### timeit

```

 py -m timeit --setup 'from harmonic_mean import harmonic_mean' --setup 'from random import randint' --setup 'nums=[randint(1,1_000_000) for _ in range(1_000_000)]' 'harmonic_mean(nums)'
 
10 loops, best of 5: 28.3 msec per loop


```


### tox

```
tox -e get_my_ip
```