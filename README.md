paper-fab-speed-dial [![Bower version](https://badge.fury.io/bo/paper-fab-speed-dial.svg)](http://badge.fury.io/bo/paper-fab-speed-dial) [![Travis state](https://travis-ci.org/Collaborne/paper-fab-speed-dial.svg?branch=master)](https://travis-ci.org/Collaborne/paper-fab-speed-dial)  [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Collaborne/paper-fab-speed-dial)
=========

`paper-fab-speed-dial` provides components to build a material design [Floating Action Button with Speed Dial](https://www.google.com/design/spec/components/buttons-floating-action-button.html#buttons-floating-action-button-transitions). The web component is built with [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")

To use this element:

`bower install paper-fab-speed-dial`

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="paper-fab-speed-dial.html">
    <link rel="import" href="paper-fab-speed-dial-action.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-fab-speed-dial with-backdrop>
    <paper-fab-speed-dial-action icon="icons:content-copy">Copy</paper-fab-speed-dial-action>
    <paper-fab-speed-dial-action icon="icons:print">Print</paper-fab-speed-dial-action>
</paper-fab-speed-dial>
```


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    