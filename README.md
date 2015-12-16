paper-fab-speed-dial [![Bower version](https://badge.fury.io/bo/paper-fab-speed-dial.svg)](http://badge.fury.io/bo/paper-fab-speed-dial) [![Travis state](https://travis-ci.org/Collaborne/paper-fab-speed-dial.svg?branch=master)](https://travis-ci.org/Collaborne/paper-fab-speed-dial)
=========

`paper-fab-speed-dial` provides components to build a material design [Floating Action Button with Speed Dial](https://www.google.com/design/spec/components/buttons-floating-action-button.html#buttons-floating-action-button-transitions). The web component is built with [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")


## Usage

`bower install paper-fab-speed-dial`

```html
<paper-fab-speed-dial>
  <paper-fab-speed-dial-action icon="icons:content-copy">Copy</paper-fab-speed-dial-action>
  <paper-fab-speed-dial-action icon="icons:print">Print</paper-fab-speed-dial-action>
</paper-fab-speed-dial>
```


## Properties & styles

These styles are available for `paper-fab-speed-dial`:

Style                                            | Description
------------------------------------------------ | ------------
--paper-fab-speed-dial-background                | The background color of the Floating Action Button
--paper-fab-speed-dial-keyboard-focus-background | The background color of the Floating Action Button when focused

These properties are available for `paper-fab-speed-dial-action`:

Property | Type    | Description
-------- | ------- | ----------------------------
**icon** | String  | Icon that is shown next to the content

Style                                                   | Description
------------------------------------------------------- | ------------
--paper-fab-speed-dial-action-background                | The background color of the Floating Action Button
--paper-fab-speed-dial-action-keyboard-focus-background | The background color of the Floating Action Button when focused


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
    