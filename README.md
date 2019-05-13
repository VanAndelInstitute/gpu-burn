# gpu-burn
Multi-GPU CUDA stress test
http://wili.cc/blog/gpu-burn.html

```
Usage gpu_burn [-r runtime_in_seconds] [-i gpu_id] [-d]
	-r runtime_in_seconds : how many seconds to run, defaults to 10sec if not specified
	-i gpu_id : which specific gpu to run on. If not specified will run on all gpus
	-d : use double precision, if not set, will use single precision
```

