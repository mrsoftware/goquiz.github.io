# Awesome Go Interview Questions and Answers

Available at [https://goquiz.github.io/](https://goquiz.github.io/)

In place editing and execution is supported.

Any feedback would be greatly appreciated.

# Category

<!--CATEGORY_BEGIN-->

[Language Specification](https://goquiz.github.io/#lang-spec)
- [Subslice](https://goquiz.github.io/#subslice-grow)
- [Short Declairation](https://goquiz.github.io/#short-declairation)
- [Nil Interfaces](https://goquiz.github.io/#interface-nil)
- [Map Ok-Idiom](https://goquiz.github.io/#map-ok-idiom)
- [Pointers](https://goquiz.github.io/#pointer)
- [interface{} Pointers](https://goquiz.github.io/#empty-interface)
- [Temporary Pointer](https://goquiz.github.io/#for-pointer)
- [Break Outer Loop](https://goquiz.github.io/#label-break)
- [Global Varibles](https://goquiz.github.io/#global-varible)
- [Defer Stack](https://goquiz.github.io/#defer-closefile)
- [Panic Stack](https://goquiz.github.io/#defer-panic)
- [recover()](https://goquiz.github.io/#defer-recover)
- [Goroutine Closures](https://goquiz.github.io/#goroutine-closure)
- [Type Shadowing](https://goquiz.github.io/#type-shadowing)
- [String to Bytes](https://goquiz.github.io/#string-bytes)
- [Map Mutex](https://goquiz.github.io/#mutex-map)
- [DeepEqual](https://goquiz.github.io/#DeepEqual)
- [Gosched](https://goquiz.github.io/#Gosched)
- [Map Immutability](https://goquiz.github.io/#map-addressing)
- [Slice Sorting](https://goquiz.github.io/#sort-Slice)

[Standard library and Packages](https://goquiz.github.io/#lib-pack)
- [init()](https://goquiz.github.io/#init-import)
- [json unmarshalling](https://goquiz.github.io/#json-unmarshal)
- [utf8 length](https://goquiz.github.io/#utf8-len)
- [regex multiline mode](https://goquiz.github.io/#regex-multiline)
- [readline](https://goquiz.github.io/#readline)
- [Heap](https://goquiz.github.io/#container-heap)
- [context.WithTimeout](https://goquiz.github.io/#context-withtimeout)
- [flag](https://goquiz.github.io/#flag)
- [text-template](https://goquiz.github.io/#text-template)
- [html-template](https://goquiz.github.io/#html-template)
- [http server](https://goquiz.github.io/#http-server)
- [sql query](https://goquiz.github.io/#sql-query)

[Toolchain](https://goquiz.github.io/#toolchain)
- [gcflags](https://goquiz.github.io/#gcflags)
- [benchmark](https://goquiz.github.io/#benchmark-N)
- [package management](https://goquiz.github.io/#vendor-gopath)
- [GOMAXPROCS](https://goquiz.github.io/#GOMAXPROCS)
- [shared object](https://goquiz.github.io/#shared-object)
- [GODEBUG](https://goquiz.github.io/#GODEBUG)
- [$GOROOT vs $GOPATH](https://goquiz.github.io/#GOROOT-GOPATH)
- [go generate](https://goquiz.github.io/#go-generate)
- [http server的pprof](https://goquiz.github.io/#http-pprof)
- [./...](https://goquiz.github.io/#path-wildcard)

[Internals](https://goquiz.github.io/#internals)
- [String Internals](https://goquiz.github.io/#unsafe-bytes-string)
- [Slice Internals](https://goquiz.github.io/#unsafe-slice-array)
- [defer overhead](https://goquiz.github.io/#defer-overhead)
- [Map malloc Threshold](https://goquiz.github.io/#map-malloc)
- [runtime.newobject()](https://goquiz.github.io/#runtime-newobject)
- [SSA](https://goquiz.github.io/#SSA)
- [AST](https://goquiz.github.io/#AST)
- [Go Bootstrapping](https://goquiz.github.io/#bootstrap)
- [Unbuffered and Buffered Channels](https://goquiz.github.io/#channel-buffering)
- [Destructor](https://goquiz.github.io/#finalizer)
- [Garbage Collection](https://goquiz.github.io/#gc)
- [Goroutine Sleep](https://goquiz.github.io/#goroutine-sleep)
- [Memory Allocation](https://goquiz.github.io/#object-memory)
- [Stack vs Heap](https://goquiz.github.io/#stack-heap)
- [Goroutine Pause or Halt](https://goquiz.github.io/#stop-goroutine)


<!--CATEGORY_END-->

# Build locally

Prerequisites: `"gopkg.in/yaml.v2"`

    cd _build
    make html
    make readme
