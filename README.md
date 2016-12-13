<p align="center">
  <img src="https://raw.githubusercontent.com/lk-geimfari/awesomeo/master/artwork/a.w.e.s.o.m.e_o.png">
  <br>
</p>

If you are interested in Open Source and are considering to join the community of Open Source developers, 
it is possible that in this list you will find the project that will suit you. 

We don't add to list mammoth's shit. Only active projects every week.


### Languages

 - [Bash](#bash)
 - [C/C++](#c)
 - [Clojure](#clojure)
 - [Common/Emacs Lisp](#lisp)
 - [Elixir](#elixir)
 - [Erlang](#erlang)
 - [Golang](#go)
 - [Haskell](#haskell)
 - [Java](#java)
 - [JavaScript](#javascript)
 - [Lua](#lua)
 - [Python](#python)
 - [R](#r)
 - [Ruby](#ruby)
 - [Rust](#rust)
 - [Scala](#scala)
 - [Swift](#swift)


### Bash

[**git-secret**](https://github.com/sobolevn/git-secret)  —  a bash tool to store your private data inside a git repo. How’s that? Basically, it just encrypts, using gpg, the tracked files with the public keys of all the users that you trust. So everyone of them can decrypt these files using only their personal secret key. Why deal with all this private-public keys stuff? Well, to make it easier for everyone to manage access rights. There are no passwords that change. When someone is out - just delete his public key, re-encrypt the files, and he won’t be able to decrypt secrets anymore.

![git-secret](https://cdn-images-1.medium.com/max/720/0*ksb58FDyPxbZ5869.png)

---

[**dokku**](https://github.com/dokku/dokku) is an docker powered mini-Heroku. The smallest PaaS implementation you’ve ever seen.

![dokku](https://cdn-images-1.medium.com/max/720/0*2L6kj4dbuMGhKber.)

---

[**pyenv**](https://github.com/yyuu/pyenv) lets you easily switch between multiple versions of Python. It’s simple, unobtrusive, and follows the UNIX tradition of single-purpose tools that do one thing well.

![pyenv](https://camo.githubusercontent.com/0e35e6235405bbcfcc0541b52c62dbd72094dde3/68747470733a2f2f692e6779617a6f2e636f6d2f36393961353839323762373765343665373163643637346337666337613738642e706e67)



### C

[**Torch**](https://github.com/torch/torch7) is a scientific computing framework with wide support for machine learning algorithms that puts GPUs first. It is easy to use and efficient, thanks to an easy and fast scripting language, LuaJIT, and an underlying C/CUDA implementation.

![torch](https://cdn-images-1.medium.com/max/720/0*6tYC_KkQvSAAL6h3.png)

---

[**Caffe**](https://github.com/BVLC/caffe) is a deep learning framework made with expression, speed, and modularity in mind. It is developed by the Berkeley Vision and Learning Center (BVLC) and community contributors.

![caffe](https://cdn-images-1.medium.com/max/720/0*PuFfFqw5QvvXMdC7.png)

---


[**libuv**](https://github.com/libuv/libuv) is a multi-platform support library with a focus on asynchronous I/O. It was primarily developed for use by Node.js, but it's also used by Luvit, Julia, pyuv, and others.

![libduv](https://cdn-images-1.medium.com/max/720/0*_Gj_yjlEAdE7x8Hi.png)

---

[**µWS**](https://github.com/uWebSockets/uWebSockets) is one of the most lightweight, efficient & scalable WebSocket server implementations available. It features an easy-to-use, fully async object-oriented interface and scales to millions of connections using only a fraction of memory compared to the competition. While performance and scalability are two of our top priorities, we consider security, stability and standards compliance paramount. License is zlib/libpng (very permissive & suits commercial applications).

![**uws**](https://cdn-images-1.medium.com/max/720/0*2wharBiKaEguzmkS.png)

---

[**RethinkDB**](https://github.com/rethinkdb/rethinkdb)   —  the first open-source scalable database built for realtime applications. It exposes a new database access model — instead of polling for changes, the developer can tell the database to continuously push updated query results to applications in realtime. RethinkDB allows developers to build scalable realtime apps in a fraction of the time with less effort.

![rethink](https://cdn-images-1.medium.com/max/720/0*oS0KanfC9ii0SKhM.png)

---

[**Redis Desktop Manager**](https://github.com/uglide/RedisDesktopManager)  —  an Open source cross-platform Redis Desktop Manager based on Qt 5

![rdm](https://camo.githubusercontent.com/58c1eba58f659057d6db1ed01b0e7d4bd031414a/687474703a2f2f72656469736465736b746f702e636f6d2f7374617469632f696d672f66656174757265732f616c6c2e706e673f7632)


### Clojure


[**Metabase**](https://github.com/metabase/metabase) is the easy, open source way for everyone in your company to ask questions and learn from data.

![metabase](https://cdn-images-1.medium.com/max/720/0*1hEfM4l394n4NlkR.png)

---

[**compojure**](https://github.com/weavejester/compojure)  —  a small routing library for Ring that allows web applications to be composed of small, independent parts.

This small Compojure application demonstrates creating a Ring handler from two routes:

```clojure
(ns hello-world.core
  (:require [compojure.core :refer :all]
            [compojure.route :as route]))
(defroutes app
  (GET "/" [] "<h1>Hello World</h1>")
  (route/not-found "<h1>Page not found</h1>"))
```

---

[**Aleph**](https://github.com/ztellman/aleph) exposes data from the network as a Manifold stream, which can easily be transformed into a java.io.InputStream, core.async channel, Clojure sequence, or many other byte representations. It exposes simple default wrappers for HTTP, TCP, and UDP, but allows access to full performance and flexibility of the underlying Netty library.

![aleph](https://cdn-images-1.medium.com/max/720/0*5fSwMgOlFvdKvvKR.png)

---

[**Datascript**](https://github.com/tonsky/datascript)  —  an immutable in-memory database and Datalog query engine in Clojure and ClojureScript.

![datascript](https://cdn-images-1.medium.com/max/720/1*VcZuVmpc41Vduc3ZUFXz3g.png)

---

[**Quil**](https://github.com/quil/quil) is a Clojure/ClojureScript library for creating interactive drawings and animations.

![quil](https://camo.githubusercontent.com/90bc972502b59f7b670dd3c249a7cfc9796f8d23/687474703a2f2f636c6f75642e6769746875622e636f6d2f646f776e6c6f6164732f7175696c2f7175696c2f7175696c2e706e67)

---

[**yada** ](https://github.com/juxt/yada) —  a web library for Clojure, designed to support the creation of production services via HTTP.

Typically, yada handlers are created from a configuation expressed in data.

```clojure
(require '[yada.yada :as yada])

(yada/handler
  {:methods
    {:get
      {:produces "text/html"
       :response "<h1>Hello World!</h1>"}}})
```

---

[**Hoplon**](https://github.com/hoplon/hoplon)  —  a set of tools and libraries for making web applications.

![hoplon](https://camo.githubusercontent.com/75c776f58649a9aeb79835f37eefef65fc508df9/687474703a2f2f686f706c6f6e2e696f2f696d616765732f6c6f676f732f686f706c6f6e2d6c6f676f2e706e67)

---

### Lisp

[**Magit**](https://github.com/magit/magit) is an interface to the version control system Git, implemented as an Emacs package. Magit aspires to be a complete Git porcelain. While we cannot claim that Magit wraps and improves upon each and every Git command, it is complete enough to allow even experienced Git users to perform almost all of their daily version control tasks directly from within Emacs. While many fine Git clients exist, only Magit and Git itself deserve to be called porcelains.

![magit](https://cdn-images-1.medium.com/max/720/0*kPc9uZd0tipuHwz8.)

---

[**Woo**](https://github.com/fukamachi/woo) is a fast non-blocking HTTP server built on top of libev. Although Woo is written in Common Lisp, it aims to be the fastest web server written in any programming language.

How fast?

![woo](https://github.com/fukamachi/woo/raw/master/images/benchmark.png)

---

[**Clack**](https://github.com/fukamachi/clack) is a web application environment for Common Lisp inspired by Python’s WSGI and Ruby’s Rack.

Example:
```common-lisp
(defvar *handler*
    (clack:clackup
      (lambda (env)
        (declare (ignore env))
        '(200 (:content-type "text/plain") ("Hello, Clack!")))))
```

---

[**Alchemist** ](https://github.com/tonini/alchemist.el) —  an Elixir Tooling Integration Into Emacs. Alchemist comes with a bunch of features, which are:

 - Mix integration
 - Compile & Execution of Elixir code
 - Inline code evaluation
 - Inline macro expanding
 - Documentation lookup
 - Definition lookup
 - Powerful IEx integration
 - Smart code completion
 - Elixir project management
 - Phoenix support
 - Integration with company-mode

![alchemist](https://raw.githubusercontent.com/tonini/alchemist.el/master/images/alchemist_logo.png)


### Elixir
### Erlang
### Go
### Haskell
### Java
### JavaScript
### Lua
### Python
### R
### Ruby
### Rust
### Scala
### Swift
