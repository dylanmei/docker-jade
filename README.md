docker-jade
-----------

Docker image to run [Jade](http://jade-lang.com) Node template engine.

simple example:

```
echo h1 Jade! | docker run -i -a stdin -a stdout dylanmei/jade -P
```

complex example:

```
docker run --rm -v $(pwd):/mnt/jade -w /mnt/jade dylanmei/jade blog.jade --out blog.html
```
