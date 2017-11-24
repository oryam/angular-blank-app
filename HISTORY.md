# HISTORY

Quick overview of modifications

**Installation**

```
npm install -g @angular/cli
ng new angular-blank --style=scss --prefix=app --routing=true
ng g component home --spec=false
ng g pipe color
ng g service blank --spec=false
```

- Modify package.json with fixed version (remove ~ and ^)
- Check latest version if needed
- Use angular cli proxy config

**Service mock**

`npm install mockyeah --save-dev`

**Polyfill / operator**

```
// RX
import 'rxjs/add/observable/merge';

import 'rxjs/add/operator/catch';
import 'rxjs/add/operator/do';
import 'rxjs/add/operator/debounceTime';
import 'rxjs/add/operator/distinctUntilChanged';
import 'rxjs/add/operator/map';
import 'rxjs/add/operator/switchMap';
import 'rxjs/add/operator/toPromise';
```

**Material**

```
npm install --save @angular/material @angular/cdk
npm install --save @angular/animations
npm install --save web-animations-js
npm install --save hammerjs
```

- add polyfill
- add material icon (cdn or locally)

**Flex layout**

`npm install @angular/flex-layout --save`

