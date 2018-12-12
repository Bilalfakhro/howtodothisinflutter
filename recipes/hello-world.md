import Example from '../components/md/Example';

<Example reactnative>

```js
import React, { Component } from 'react';
import { Text, View, AppRegistry } from 'react-native';
import { name as appName } from './app.json';

export default class HelloWorldApp extends Component {
  render() {
    return (
      <View>
        <Text>Hello world!</Text>
      </View>
    );
  }
}

AppRegistry.registerComponent(appName, () => App);
```

</Example>

<Example flutter>

```dart
import 'package:flutter/material.dart';

void main() {
    runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Hello world!',
      home: Scaffold(
        body: Center(
          child: Text('Hello world'),
        ),
      ),
    );
  }
}
```

</Example>
