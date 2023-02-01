<h1 align="center">
NGX-KEYPAD
</h1>

# NGX-KEYPAD

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

[Demo Link](https://keypad-angular.netlify.app/)

## :star: Give a Star!
If you like or are using this project please give it a star [here](https://github.com/MrHassanKhan/keypad-angular). Thanks!

## ✨ Features

- Numbers with mask so it is can use as password.
- Hide display if you want.
- Maximum length for input string.
- *,# buttons included

## 🔨 Usage

Import the component modules you want to use into your `app.module.ts` file and [feature modules](https://angular.io/guide/feature-modules).

```ts
import {NgxKeypadModule} from 'ngx-keypad';

@NgModule({
  imports: [ NgxKeypadModule ]
})
export class AppModule {
}
```

In your template write this code.
```html
<keypad [showPeriod]="true" [isPassword]="false" [(data)]="result"></keypad>
```

## Screenshot

![image](https://user-images.githubusercontent.com/23718443/216028355-41d18056-b973-4d84-99bf-895b17fb9e3f.png)


## Properties

| Property | Description | Type | Default |
| --- | --- | --- | --- |
| [showDisplay] | Show Display or not | boolean | true |
| [showPeriod] | Show period button or not | boolean | true |
| [isPassword] | Write asterisk in the field | boolean | false |
| [maxLength] | Not allow more length than this max, null is unlimited | number | null |
| [maxNumber] | Not allow more number than this max, null is unlimited | number | null |
| [background] | Component background | string | '#ccc' |
| [width] | Component width can be for ex 400px | string | '100%' |
| [padding] | Component padding can be for ex 20px | string | '10px' |
| [(data)] | Data input and output | string | '' |
