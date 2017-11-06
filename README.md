# contributions-chart

> A contributions record imitated github

## Installation

Using npm
```javascript
npm i --save contributions-chart
```
**ES2015**

```javascript
import { VueContributionsChart } from 'contributions-chart'
```

## Usage

```javascript
<vue-contributions-chart :contributions="contributions"></vue-contributions-chart>
```

```javascript
new Vue({
  el: '#app',
  data: {
    contributions: [
      {
        date: '2017-03-04',
        value: 3
      },
      {
        date: '2017-11-05',
        value: 10
      }
    ]
  }
});
```

## Props
|Prop|Description|
|----|-----------|
|year|Which year  e.g. 2017|
|cellSize| Size of every single cell(default: 14px)|
|width| Width of chart(default: adapt to content)|
|height| Height of chart(default: adapt to content)|
|interval| Interval of cells(default: 1px)|
|textFontsize| Font size of leftside text|
|contributions| Array |

## Result
![](http://7xva4j.com1.z0.glb.clouddn.com/contributions-chart.png)