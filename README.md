# \<ethjs-element\>

A webcomponent that uses ethjs to intereact with the Ethereum Blockchain

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) and npm (packaged with [Node.js](https://nodejs.org)) installed. Run `npm install` to install your element's dependencies, then run `polymer serve` to serve your element locally.

## Install ethjs-element

```
$ npm install ethjs-element
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```
## Import

```
$ import 'ethjs-element';
```

## Basic Use

```html
<ethjs-element  
    eth="{{eth}}"
    http-provider="https://ropsten.infura.io">
</ethjs-element>
```