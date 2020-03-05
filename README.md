# <h1 align="center">auto-chart 👋</h1>

## [实际仓库链接](https://github.com/linwaiwai/autochart-solution)

## 仓库内容

1、前端支撑库React-Auto-Chart的支持；即react-auto-chart 源码

2、后端多数数据源驱动Graphreport_Drive库支持；

3、前端使用react-auto-chart微服务Demo;

4、前端微服务管理Graphreport_Admin_Frontend支持；即管理平台前端代码

5、后端图表管理Graphreport_Admin_Backedn支持；即管理平台后端代码

### 购买链接

商业版本代码已加密，购买链接 http://pay.openapplus.com/pay?money=500&type=1

## 使用方法（react-auto-chart）

<h1 align="center">Welcome to react-auto-chart 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.3-blue.svg?cacheSeconds=2592000" />
  <img src="https://img.shields.io/badge/node-%3E%3D8.0.0-blue.svg" />
  <a href="https://www.npmjs.com/package/@openapplus/react-auto-chart" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="#" target="_blank">
    <img alt="License: GPL--3.0" src="https://img.shields.io/badge/License-GPL--3.0-yellow.svg" />
  </a>
  <a href="https://twitter.com/linwaiwai" target="_blank">
    <img alt="Twitter: linwaiwai" src="https://img.shields.io/twitter/follow/linwaiwai.svg?style=social" />
  </a>
</p>

> auto chart component for online editing, include a auto chart or combination chart to your react app

### 🏠 [Homepage](https://github.com/linwaiwai/autochart)

### ✨ [Demo](http://www.openapplus.com/admin/#/online/graphreport)

## Prerequisites

- node >=8.0.0

## Install

```sh
* npm install --save @openapplus/react-auto-chart
```

## Usage

* open http://www.openapplus.com/admin/#/online/graphreport
* register and login
* create connect to your datasource (mysql, es, redis, mongo)
* create chart or templet according the add form 
* get the link by viewing the chart item. copy the last path component as a code
* write the code 
```javascript
import React, { Component } from 'react';
import PropTypes from 'prop-types';
import { GraphreportAutoChart } from '@openapplus/react-auto-chart';

export default class OnlGraphreportAutoChart extends Component  {
	render() {
		const {
			match: {
				params: { code },
			}
		} = this.props;
		return (<GraphreportAutoChart code={code} ></GraphreportAutoChart>);
	}

}
```
* need the complete demo, just click the link https://github.com/linwaiwai/autochart, and read the license note

## Run tests

```sh
yarn run test
```

## License

/*
 * GPLv3 License
 *
 * A library named React Auto Chart to draw chart according json configuration 
 *
 * Copyright (C) 2020  linwaiwai(jiansihun@foxmail.com)
 * 
 * This program is free software: you can redistribute it and/or modify
 * it under the terms of the GNU General Public License as published by
 * the Free Software Foundation, either version 3 of the License, or
 * (at your option) any later version.
 * 
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 * 
 * You should have received a copy of the GNU General Public License
 * along with this program.  If not, see <https://www.gnu.org/licenses/>.
 * 
 * Note:
 * 
 * This library is using opensource license GPLv3.
 * 
 * If your want to have it for commerce use, please contract author to be granted. 
 * 
 * All the income will be donated to support the work of doctor at Wuhan Province in China until the epidemic of Wuhan ends.
 * 
 * Commerce authorization package will include frontend and backend solution, in which The frontend solution includes auto chart component and a micro frontend service which contains admin tools for json configuration, the backend is a SDK tool based on the SpringBoot.
 * 
 * All this will cost you only 500 yuan/year for public welfare. What a good deal.
 * 
 * How to use: https://www.jianshu.com/p/81e094dc7e88
 * Demo Link: http://www.openapplus.com/admin/#/online/graphreport
 * Test acount: autochart , passsword autochart
 *
 */

## Author

👤 **linwaiwai**

* Website: http://www.openapplus.com
* Twitter: [@linwaiwai](https://twitter.com/linwaiwai)
* Github: [@linwaiwai](https://github.com/linwaiwai)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/linwaiwai/autochart/issues). 

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
