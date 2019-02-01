# AST-Clang
How to use:

make CC=/path/to/ast-clang CXX=/path/to/ast-clang

For configure:

./configure CC=/path/to/ast-clang
make 


how to find all ast files:

find -name "*.ast" | xargs file

Remove files whose type is not data
