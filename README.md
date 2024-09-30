**What is PyLLVM?**
PyLLVM is the unoffical LLVM package for 
python. keep in mind this package was 
created to be used in the zed compiler


**Dose PyLLVM Come With Prebuilt Binaries For LLVM?**
No PyLLVm does not come with pre bulit Binaries for llvm 
PyLLVM requires the user to have llc, ld or lld if these
tools are not installed it will defualt to clang if clang
is not installed it will throw an error you will still be
able to generate llvm code just not compile it
