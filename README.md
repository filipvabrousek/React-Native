# React Native
Learning React Native since 10/01/2020

```js
export default class Hello extends Component{
  render(){
    return(
      <View>
        <Text>Hello!</Text>
      </View>
    );
  }
}
```

```js
const styles = StyleSheet.create({
  gr: {
    color: "green",
  }
});

export default class Imager extends Component {
  render(){
    return(
  <View>
   <Text style={styles.gr}>Green</Text>
  </View>
    );
  }
}
```
