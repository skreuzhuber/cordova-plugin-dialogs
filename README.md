<!---
 license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.
-->

# cordova-plugin-dialogs

For general information please consult the official plugin documentation: https://github.com/apache/cordova-plugin-dialogs

This project extendend the cordova-plugin-dialogs with possibilities to specify an "inputType" for the "prompt(...) method. 
Supported values for "inputType" include:
* "numeric"
* "alphanumeric"
* "numericPassword"
* "alphanumericPassword"

Where numeric values aim to display a keyboard containing only numbers. Password values hide the entered characters.

A sample call for a pin input dialog:
`navigator.notification.prompt("Please enter your PIN:", callback, "Login", ["OK", "Cancel"], "", "numbericPassword");`

## Supported platforms
* Android

## Future plans
* iOS will be supported shortly
