# IBM easy multi arch build

I recommend visiting this link first to see my prior builds: https://travis-ci.com/github/Montana/ibm-easy-multiarch/builds/214082235.

This `.travis.yml` file tests my quick Python app I made entitled `hello.py`, and to show off a multi arch build: 

```python
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
    
# Used Python 3.7 for different testing on the IBM multi arch builds
# Author Montana Mendy
```

It built `hello.py` very quickly, and was extremely straight forward, in all three archs.

### End Result 

It built my Python script with the correct answer which is `x=1`:

![Python](python.png) 

All three `archs` built, and ran my `hello.py` script:

![Builds](builds.png)
