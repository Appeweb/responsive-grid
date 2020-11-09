# Appeweb-Grid

## Description

Simple scss/css responsive grid

## Installation

install with `yarn add appeweb-grid` or `npm -i appeweb-grid`

## Basics usage
### Import *appeweb-grid*
#### Option A:
Link the CSS file directly if you agree for use defaults parameters, like so:

`<link href=".../appeweb-grid/dist/css/index.css">`

#### Option B (Recommended) : 
Import **grid.scss** in your sass file

`@import "appeweb-grid/src/sass/grid.scss"`

### Use appeweb-grid

There are two types of **container**
Container with marge and max width in terms of screen size.
````
<div class="container">
    <!-- your content -->
</div>
````
Container with no marge and take 100% of parent.
````
<div class="container-fluid">
    <!-- your content -->
</div>
````

Using grid columns
````
<div class="container or container-fluid">
    <div class="row">
        <div class="col-1 ... 12">
            <!-- your content -->
        </div>
    </div>
</div>
````