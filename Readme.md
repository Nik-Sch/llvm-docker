build with `docker build -t llvm:6.0 .`
run make with `docker run -ti --rm --user $(id -u):$(id -g) -v $(pwd):/work llvm:6.0 make`
