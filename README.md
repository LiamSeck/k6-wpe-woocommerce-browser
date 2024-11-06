[![k6](https://img.shields.io/badge/k6-7D64FF.svg?style=for-the-badge&logo=k6&logoColor=white)](https://github.com/grafana/k6)![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black)

# K6 Browser Script 
## Overview

This repo contains an example K6 browser script simulating a full checkout flow against a WooCommerce installation hosted at WPE: https://liamseprod.wpenginepowered.com/. 


### Execution Steps

```
K6_BROWSER_HEADLESS=false k6 run browser-checkout.js
```  
