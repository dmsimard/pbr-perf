```
$ time tox -e debug
debug create: /home/dmsimard/dev/sandbox/pbr-perf/.tox/debug
debug develop-inst: /home/dmsimard/dev/sandbox/pbr-perf
debug installed: -e git+git@github.com:dmsimard/pbr-perf.git@3c8b6eaadd26fb4dd2dd54077fcb25687f652944#egg=perf
debug runtests: PYTHONHASHSEED='304440903'
debug runtests: commands[0] | python -c from perf import test; test.hello_world()
hello world
_________________________________________________________________________________________________________________________________________ summary __________________________________________________________________________________________________________________________________________
debug: commands succeeded
congratulations :)
121.91user 33.02system 2:35.68elapsed 99%CPU (0avgtext+0avgdata 611236maxresident)k
0inputs+25400outputs (0major+600670minor)pagefaults 0swaps
```
