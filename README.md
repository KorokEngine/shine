# Shine

It's a combination of `x/exp/shiny` and `x/mobile`, so named Shine. The main idea of Shine is to provide a
stable/easy-use/cross-platform basic graphics context for golang.


1. driver provide windows system
2. gl provide gl-binding

'gl' module forked from 'https://github.com/goxjs/gl' which originally forked from 'go/mobile' (a very early version).
'driver' module use go-glfw to adapter desktop, glfw is Good enough to handle this. For mobile system like Android/iOS,
we forked some code from `go/mobile`.

**Don't do experiments, make it works and stable!**
