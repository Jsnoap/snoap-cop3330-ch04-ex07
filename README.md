To remove compile warnings "warning: alias declarations are a C++11 extension [-Wc++11-extensions]" : May need to  compile program with the following tag "-std=c++11"

Example (on MacOS): clang++ singleDigitCalc.cpp -std=c++11
