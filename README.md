# 🥞 Wagyuswap UIkit

[![Version](https://img.shields.io/npm/v/@wagyuswap-core/uikit)](https://www.npmjs.com/package/@wagyuswap-core/uikit) [![Size](https://img.shields.io/bundlephobia/min/@wagyuswap-core/uikit)](https://www.npmjs.com/package/@wagyuswap-core/uikit)

Wagyuswap UIkit is a set of React components and hooks used to build pages on Pancake's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @wagyuswap-core/uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@wagyuswap-core/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@wagyuswap-core/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
