# highchart-commonjs

This is a simple wrapper for highcharts that allows using it with webpack.

The reason why this project is better is because little robot updates this package regularly with the latest version of highcharts. 

This fork exists because kirjs/commonjs-highcharts seems to depend on the non-release version of Highcharts, and we at SpotOn were not able to get that to build as part of our Webpack processes.

This fork also simplifies the file structure and removes all the demo and Gulp business, which we don't need in simple CommonJS library for our purposes.

# Installation

```bash
npm install highcharts-release SpotOnInc/commonjs-highcharts --save
```

# Usage

```js
import highcharts from 'commonjs-highcharts'
```
