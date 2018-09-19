# react-native-elements-input-password
React Native Elements show or hide input password

---

## Install
`npm i react-native-elements-input-password`

## Example

```
import InputPassword from 'react-native-elements-input-password';

<InputPassword
    label="Password"
    value={this.state.regPassword}
    onChangeText={ (regPassword) => this.setState({ regPassword }) }
/>
```