# Chapi Domain MultiplePlatform

## Usage

### Setup Java

1. add deps

```
repositories {
    ...
    maven {url  "https://dl.bintray.com/phodal/chapi"}
}
```

and

```
dependencies {
    implementation 'com.phodal.chapi:chapi-domain:0.1.1'
}
```

2. Usage in Code

```
package teapi.application

import chapi.domain.core.CodeDataStruct

fun main(): String  {
    val codeDataStruct = CodeDataStruct()
    ...
}

```

### Setup JavaScript

1. add deps

`yarn add @chapi/domain` or `npm install --save @chapi/domain`

2. Usage In Code

```
var chapi = require("@chapi/domain").chapi.domain.core;

var dataStruct = new chapi.CodeDataStruct("Hello");
console.log(dataStruct);
```


## Setup

### publish package

```
./gradlew bintrayUpload
```


License
---

[![Phodal's Idea](http://brand.phodal.com/shields/idea-small.svg)](http://ideas.phodal.com/)

@ 2020 A [Phodal Huang](https://www.phodal.com)'s [Idea](http://github.com/phodal/ideas).  This code is distributed under the MPL license. See `LICENSE` in this directory.
