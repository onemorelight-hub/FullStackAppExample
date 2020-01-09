#### We will set up our project to use Angular Material and Angular Flex Layout.

Configure your Angular Project to use Angular Material

#### To configure your project to use Angular material, type the following at the prompt to install Angular Material, Angular Animations and HammerJS:

npm install @angular/material@6.4.7 --save

npm install @angular/cdk@6.4.7 --save

npm install --save @angular/animations@6.1.7

npm install --save hammerjs@2.0.8

Configure to use Material Design Icons


#### Next, include the following into the <head> of index.html to make use of Material Design icons:

<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel ="stylesheet">

#### Configure your Angular Project to use Flex Layout

##### Next, install Angular Flex Layout as follows:

npm install --save @angular/flex-layout@6.0.0-beta.18

#### Updating AppModule

Then, you need to import the Angular Animations Module, Angular Material Toolbar Module, Flex Layout Module and hammerjs into your root module (src/app/app.module.ts) as follows:

. . . 

import { BrowserAnimationsModule } from '@angular/platform-browser/animations';

import { MatToolbarModule } from '@angular/material/toolbar'; 

import { FlexLayoutModule } from '@angular/flex-layout';

. . . 

import 'hammerjs';

@NgModule({
  
  . . . 
  
  imports: [ 
    
    . . .,
    
    BrowserAnimationsModule,
    MatToolbarModule,
    FlexLayoutModule
    
  ], 
    
    . . . 
  
  
}) 
. . . 


#### Adding a Material Toolbar

Open app.component.html and replace its contents with the following code:

<mat-toolbar color="primary"> <span>Ristorante Con Fusion</span> </mat-toolbar>

#### Adding Styles

Add the following styles to styles.scss file:


@import '~@angular/material/prebuilt-themes/deeppurple-amber.css';

// some basic resets 

body { 
  padding: 0; 
  margin: 0;  
  font-family: Roboto, sans-serif; 
  
}

This will add a built-in Material theme to our application.

## Important Links:
### Angular Material
https://material.angular.io
### Angular Material Toolbar
https://material.angular.io/components/toolbar/overview
### Angular Flex Layout
https://github.com/angular/flex-layout
### Angular Flex Layout Documentation
https://github.com/angular/flex-layout/wiki/API-Documentation
### Best JavaScript framework
https://hackernoon.com/5-best-javascript-frameworks-in-2017-7a63b3870282#.tt1k09l1d
### Type Script tutorial 
http://www.typescriptlang.org/docs/tutorial.html
### Typescript: Migrating from JavaScript
http://www.typescriptlang.org/docs/handbook/migrating-from-javascript.html

