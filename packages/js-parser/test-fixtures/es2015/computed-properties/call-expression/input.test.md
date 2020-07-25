# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > computed-properties > call-expression`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/computed-properties/call-expression/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/computed-properties/call-expression/input.js"
		end: Object {
			column: 0
			index: 29
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "es2015/computed-properties/call-expression/input.js"
				end: Object {
					column: 2
					index: 28
					line: 3
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "es2015/computed-properties/call-expression/input.js"
					end: Object {
						column: 2
						index: 28
						line: 3
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "foo"
							loc: Object {
								filename: "es2015/computed-properties/call-expression/input.js"
								identifierName: "foo"
								end: Object {
									column: 7
									index: 7
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/computed-properties/call-expression/input.js"
							end: Object {
								column: 1
								index: 27
								line: 3
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSObjectExpression {
							loc: Object {
								filename: "es2015/computed-properties/call-expression/input.js"
								end: Object {
									column: 1
									index: 27
									line: 3
								}
								start: Object {
									column: 10
									index: 10
									line: 1
								}
							}
							properties: Array [
								JSObjectProperty {
									key: JSComputedPropertyKey {
										value: JSCallExpression {
											arguments: Array []
											loc: Object {
												filename: "es2015/computed-properties/call-expression/input.js"
												end: Object {
													column: 8
													index: 20
													line: 2
												}
												start: Object {
													column: 3
													index: 15
													line: 2
												}
											}
											callee: JSReferenceIdentifier {
												name: "bar"
												loc: Object {
													filename: "es2015/computed-properties/call-expression/input.js"
													identifierName: "bar"
													end: Object {
														column: 6
														index: 18
														line: 2
													}
													start: Object {
														column: 3
														index: 15
														line: 2
													}
												}
											}
										}
										loc: Object {
											filename: "es2015/computed-properties/call-expression/input.js"
											end: Object {
												column: 9
												index: 21
												line: 2
											}
											start: Object {
												column: 2
												index: 14
												line: 2
											}
										}
									}
									value: JSStringLiteral {
										value: ""
										loc: Object {
											filename: "es2015/computed-properties/call-expression/input.js"
											end: Object {
												column: 13
												index: 25
												line: 2
											}
											start: Object {
												column: 11
												index: 23
												line: 2
											}
										}
									}
									loc: Object {
										filename: "es2015/computed-properties/call-expression/input.js"
										end: Object {
											column: 13
											index: 25
											line: 2
										}
										start: Object {
											column: 2
											index: 14
											line: 2
										}
									}
								}
							]
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```