```
$ time tox -e debug
debug develop-inst-noop: /home/dmsimard/dev/sandbox/pbr-perf
debug installed: -e git+git@github.com:dmsimard/pbr-perf.git@885b66032ae8d2ef952e7f666317b8fe99cff1ae#egg=perf
debug runtests: PYTHONHASHSEED='3320173742'
debug runtests: commands[0] | python -c from perf import test; test.hello_world()
hello world
_________________________________________________________________________________________________________________________________________ summary __________________________________________________________________________________________________________________________________________
debug: commands succeeded
congratulations :)
0.97user 0.14system 0:01.11elapsed 100%CPU (0avgtext+0avgdata 33468maxresident)k
0inputs+8outputs (0major+46125minor)pagefaults 0swaps
```
