Check out with gclient:
```
$ gclient config https://domain-registry-provider.googlecode.com/svn/trunk/src
$ gclient sync --force
```

Build it:
```
$ cd src/
$ make
```

Run the tests:
```
$ out/Default/domain_registry_test
```

The tests should pass.  If not, please file a bug.