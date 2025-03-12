# How to build

step1
```
>>git clone https://github.com/madhawapolkotuwa/SimpleUnitTestExample.git
```

step2
```
>>mkdir build
>>cmake -S . -B build
>>camke --build build -j 12
>>GTEST_COLOR=1 ctest --test-dir build --output-on-failure -j 12
```