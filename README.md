# AsyncTickPhysics

This is a plugin to allows easy access to the new Async Physics introduced in UE5, to be used in blueprints or C++

### Instructions
- Change the parent of your pawn class to AsyncTickPawn
- Override the Async Tick event
- Use the ATP_* functions provided to manipulate the component

You can only use this plugin in a c++ project, if you need to convert your project: create a new c++ class (Tools > Add new C++ class), Right Click your .uproject file and select Generate Visual studio project files. You should now be able to use the plugin :)

### Example
![Image](https://i.imgur.com/UjC4Yyl.png)

## License

MIT License

Copyright (c) 2022 Alex Craig

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

