+++
title: "Notes about JS"
description: "Short notes about JS"
date: 2021-03-13T22:21:11+03:00
draft: false
+++


Let vs Var vs Const
-------------------

var:
	function scoped
	has `undefined` value when accessing a variable before it's declared

```
function fooBar(){
	console.log(testedVariable); // print 'undefined'
	var testedVariable = []

	for(i){

	}
}
```

let:
	block scoped
