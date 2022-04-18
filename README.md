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
        ThebrioflashynavbarItem(
          icon: Icon(Icons.settings),
          title: Text('한국어'),
        ),
      ],
),
```
