### React Native Social Buttons

<p>
<img src="https://github.com/virtumonde/openlayers-typescript-boilerplate/raw/master/openlayers.png" />
</p>


## Installation

```bash
yarn add react-native-social-buttons

or

npm install react-native-social-buttons
```

## Basic Usage

```jsx
import React from "react";
import { View } from "react-native";
import { FacebookSocialButton } from "react-native-social-buttons";

export default class App extends React.Component {
  render() {
    return (
      <View>
        <FacebookSocialButton onPress={() => {}} buttonViewStyle={...} logoStyle={...} textStyle={...} />
      </View>
    );
  }
}
```

You can costumize the buttons using buttonViewStyle={...}, logoStyle={...} and textStyle={...}
