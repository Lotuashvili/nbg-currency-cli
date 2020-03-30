# NBG Currency CLI

Command-line tool for National Bank of Georgia currency service.

> **Note:** If you're looking for a non-cli PHP package, check out [stichoza/nbg-currency](https://github.com/Stichoza/nbg-currency) instead.

<div style="align: center">
  <img width="885" alt="Screen Shot 2020-03-30 at 05 35 39" src="https://user-images.githubusercontent.com/1139050/77867469-6a02c680-7248-11ea-82a1-b52e2de6a7f1.png">
</div>

## Installation

Install this package globally via [Composer](https://getcomposer.org/).

```
composer global require stichoza/nbg-currency-cli
```

## Usage

#### Options
`--help`           Display this help page.\
`--plain`          Display plain results without colors.\
`--normalize`      Convert rates to single entity if rate is given for amount larger than 1.

#### Example commands
`nbg usd`          Get currency rate and change for USD.\
`nbg usd --plain`  Get currency rate for USD.\
`nbg usd eur gbp`  Get currency rate for USD, EUR, GBP.\
`nbg 150 usd`      Get equivalent of 150 USD in GEL.\
`nbg 150 gel usd`  Get equivalent of 150 GEL in USD.
