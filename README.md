# minilisp

This is an implementation of minilisp in zepto, inspired by the version
in [SICP Distilled](http://www.fritzze.com/).

# Usage

````clojure
(load "mini")
(eval-program [(defn fac (n) (if (= n 0) 1 (* n (fac (- n 1)))))
               (fac 10)])
```

<hr/>

Have fun!
