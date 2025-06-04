file(GLOB LIB . *.c)
add_library(lib ${LIB})
add_test(t5 src/calculator car 5)
