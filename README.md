# Node Input - Simple Input Handling for Node.js CLI Applications

[![npm version](https://badge.fury.io/js/%40cryptzx-dev%2Fnode-input.svg)](https://www.npmjs.com/package/@cryptzx-dev/node-input)

## Overview

`@cryptzx-dev/node-input` is a lightweight package designed to simplify input handling for Node.js CLI applications. It enables developers to easily capture user input asynchronously with minimal setup.

## Features

- **Asynchronous Input**: Leverage async/await to handle user input smoothly.
- **Simple API**: Minimalistic and intuitive design for fast integration.
- **No Dependencies**: A lean package with no external dependencies.

## Installation

Install the package via npm:

```bash
npm install @cryptzx-dev/node-input
```
Usage

After installing, you can use it within your CLI applications as follows:
```JavaScript
const { input } = require("@cryptzx-dev/node-input");

(async () => {
  const inputData = await input("What's your name?");
  console.log("Your name: " + inputData);
})();
```
Example Output:
```console
> What's your name? 
> John
Your name: John
```
License

This project is open-source but not licensed. Feel free to use, modify, or distribute it at your own discretion. No warranties or guarantees are provided.
