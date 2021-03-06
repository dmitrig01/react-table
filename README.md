React Table
---

[![Build Status](http://img.shields.io/travis/NickTomlin/react-table.svg?style=flat)](https://travis-ci.org/NickTomlin/react-table)

A simple sortable table component for react.

# Usage

`npm i react-table` (non cjs users can point a `<script`> tag to the built files in `dist`)

```javasript
var React = require('react');
var ReactTable = require('react-table');
var data = [
  {favoriteColor:'blue',  age: 30, name: "Athos",      job: "Musketeer"},
  {favoriteColor: 'red' ,  age: 33, name: "Porthos",    job: "Musketeer"},
  {favoriteColor: 'blue' ,  age: 27, name: "Aramis",     job: "Musketeer"},
  {favoriteColor: 'orange' ,  age: 25, name: "d'Artagnan", job: "Guard"}
];

React.render(<ReactTable data={data} />, document.body);
```

See examples for a more full featured use case.

# Development

```bash
# watch js files and start example server
npm start

# run jest tests
npm test

# build for production
npm run build
```
