# React Redux Simple Snippets
Collection of the essentioanl Snippets for `React`, `React Native` and `Redux`.

These snippets are selected based on my own use. Not everything is included, it is meant to be a minimal collection of the essentials only.

## Works With
* JavaScript (.js)
* JavaScript React (.jsx)


# Snippets List
| Trigger   | Result |
| -------   | ------ |
| `rcc`     | React class component skeleton |
| `rccc`    | React class component with constructor skeleton |
| `rcr`     | React class component with redux connect |
| `rncc`    | React Native component skeleton |
| `rncr`    | React Native component with redux connect |
| `rfc`     | React stateless component skeleton |
| `con`     | Creates class constructor |
| `ss`      | setState shortcut |
| `imr`     | Import React |
| `imrn`    | Import React Native Element |
| `rnss`    | React Native StyleSheet |
| `reducer` | Redux Reducer skeleton |
| `action`  | Action Creator skeleton |


# Snippets

### `rcc`
```javascript
import React, { Component } from 'react';
 
class $1 extends Component {
    render() { 
        return (
            <div>
                $1
            </div>
        );
    }
}


export default $1;
```

### `rccc`
```javascript
import React, { Component } from 'react';
 
class $1 extends Component {
    constructor(props) {
        super(props);
        this.state = {};
    }
    render() { 
        return (
            <div>
               $1 
            </div>
        );
    }
}
 
export default $1;
```

### `rcr`
```javascript
import React, { Component } from 'react';
import { connect } from 'react-redux';
 
class $1 extends Component {
    render() { 
        return (
            <div>
               $1 
            </div>
        );
    }
}
 
export default connect()($1);
```

### `rncc`
```javascript
import React, { Component } from 'react';
import { View, Text, StyleSheet } from 'react-native';
 
const styles = StyleSheet.create({
    container: {
        flex: 1
    }
});
 
class $1 extends Component {
    render() { 
        return (
            <View style={styles.container}>
                <Text>$1</Text>
            </View>
        );
    }
}
 
export default $1;
```

### `rncr`
```javascript
import React, { Component } from 'react';
import { View, Text, StyleSheet } from 'react-native';
import { connect } from 'react-redux';
 
const styles = StyleSheet.create({
    container: {
        flex: 1
    }
});
 
class $1 extends Component {
    render() { 
        return (
            <View style={styles.container}>
                <Text>$1</Text>
            </View>
        );
    }
}
 
export default connect()($1);
```

### `rfc`
```javascript
import React from 'react';
 
const $1 = () => {
    return (
        <div>
            $1
        </div>
    );
}
 
export default $1;
```

### `con`
```javascript
constructor(props) {
    super(props);
    this.state = {};
}
```
### `ss`
```javascript
this.setState({ $1 })
```


### `imr`
```javascript
import React from 'react';
```

### `imrn`
```javascript
import { $1 } from 'react-native';
```

### `rnss`
```javascript
const styles = StyleSheet.create({
    $1: {
        
    }
});
```

### `reducer`
```javascript
const INITIAL_STATE = {};

export const $1 = (state = INITIAL_STATE, action) => {
    switch (action.type) {
        case $2:
            return 
        default:
            return state
    }
}
```

### `action`
```javascript
export const $1 = () => {
  return async dispatch => {
    try {
        $2
    } catch (e) {}
  };
};
```

