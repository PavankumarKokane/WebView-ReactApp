# WebView-ReactApp
<h3>Add The WebView in React<h3>
<h5>1.Past This command in cmd</h5>
<h5>2.open cmd in administrative mode</h5>
expo install react-native-webview
<h5>It Will Download Some Packages</h5>
<h5>Now create the project by expo init appname </h5>
<h3>Copy And Past The Following Code In App.tsx<h3>
  
import * as React from 'react';

import { WebView } from 'react-native-webview';

export default class App extends React.Component {

  render() {
  
    return <WebView source={{ uri: 'https://webhdtv.cf' }} style={{ marginTop: 18 }} />;
    
  }
  
}

<h5>Now run by npm start </h5>
<h5>Build Apk By Using expo build:android </h5>
