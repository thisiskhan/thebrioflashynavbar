# flashy_tab_bar
[![GitHub license](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/Cuberto/flashy-tabbar-android/master/LICENSE)

One another nice animated tabbar (Inspired by Cuberto)

![Animation](https://raw.githubusercontent.com/leesnhyun/flashy_tab_bar/master/docs/animation.gif)

## Getting Started

Add the dependency at pubspec.yaml:

```yaml
dependencies:
  ...
  thebrioflashynavbar: ^0.0.1
```

## Basic Usage

```dart
bottomNavigationBar: Thebrioflashynavbar(
     selectedIndex: _selectedIndex,
     showElevation: true,
     onItemSelected: (index) => setState(() {
       _selectedIndex = index;
     }),
     items: [
        ThebrioflashynavbarItem(
          icon: Icon(Icons.event),
          title: Text('Events'),
        ),
        ThebrioflashynavbarItem(
          icon: Icon(Icons.search),
          title: Text('Search'),
        ),
        ThebrioflashynavbarItem(
          icon: Icon(Icons.highlight),
          title: Text('Highlights'),
        ),
        ThebrioflashynavbarItem(
          icon: Icon(Icons.settings),
          title: Text('Settings'),
        ),
      ],
),
```
# 📝License
```
MIT License

Copyright (c) 2022 TheBrio

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
```
