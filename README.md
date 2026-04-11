# linked-list-library

Singly linked list with a tagged union of numeric types (int8/16/32/64, float, double), implemented in C-style C++. Provides `PushFront`, `PrintList`, and `PrintCurrentElement`, with a `Main.cpp` demo.

## Platform

Visual Studio solution (`LinkedList.sln`) targeting MSVC on Windows x64.

## Build

Open `LinkedList.sln` in Visual Studio and build, or from a Developer Command Prompt:

```bat
msbuild LinkedList.sln /p:Configuration=Debug /p:Platform=x64
```

The resulting executable runs the demo in `Main.cpp`.
