# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > declare > destructure-new-line`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/declare/destructure-new-line/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/declare/destructure-new-line/input.ts"
		end: Object {
			column: 0
			index: 50
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/declare/destructure-new-line/input.ts"
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "declare"
				loc: Object {
					filename: "typescript/declare/destructure-new-line/input.ts"
					identifierName: "declare"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/declare/destructure-new-line/input.ts"
				end: Object {
					column: 41
					index: 49
					line: 2
				}
				start: Object {
					column: 0
					index: 8
					line: 2
				}
			}
			declaration: JSVariableDeclaration {
				kind: "const"
				loc: Object {
					filename: "typescript/declare/destructure-new-line/input.ts"
					end: Object {
						column: 41
						index: 49
						line: 2
					}
					start: Object {
						column: 0
						index: 8
						line: 2
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingObjectPattern {
							rest: undefined
							loc: Object {
								filename: "typescript/declare/destructure-new-line/input.ts"
								end: Object {
									column: 40
									index: 48
									line: 2
								}
								start: Object {
									column: 6
									index: 14
									line: 2
								}
							}
							properties: Array [
								JSBindingObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "x"
											loc: Object {
												filename: "typescript/declare/destructure-new-line/input.ts"
												identifierName: "x"
												end: Object {
													column: 9
													index: 17
													line: 2
												}
												start: Object {
													column: 8
													index: 16
													line: 2
												}
											}
										}
										loc: Object {
											filename: "typescript/declare/destructure-new-line/input.ts"
											end: Object {
												column: 9
												index: 17
												line: 2
											}
											start: Object {
												column: 8
												index: 16
												line: 2
											}
										}
									}
									value: JSBindingIdentifier {
										name: "x"
										loc: Object {
											filename: "typescript/declare/destructure-new-line/input.ts"
											identifierName: "x"
											end: Object {
												column: 9
												index: 17
												line: 2
											}
											start: Object {
												column: 8
												index: 16
												line: 2
											}
										}
									}
									loc: Object {
										filename: "typescript/declare/destructure-new-line/input.ts"
										end: Object {
											column: 9
											index: 17
											line: 2
										}
										start: Object {
											column: 8
											index: 16
											line: 2
										}
									}
								}
								JSBindingObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "y"
											loc: Object {
												filename: "typescript/declare/destructure-new-line/input.ts"
												identifierName: "y"
												end: Object {
													column: 12
													index: 20
													line: 2
												}
												start: Object {
													column: 11
													index: 19
													line: 2
												}
											}
										}
										loc: Object {
											filename: "typescript/declare/destructure-new-line/input.ts"
											end: Object {
												column: 12
												index: 20
												line: 2
											}
											start: Object {
												column: 11
												index: 19
												line: 2
											}
										}
									}
									value: JSBindingIdentifier {
										name: "y"
										loc: Object {
											filename: "typescript/declare/destructure-new-line/input.ts"
											identifierName: "y"
											end: Object {
												column: 12
												index: 20
												line: 2
											}
											start: Object {
												column: 11
												index: 19
												line: 2
											}
										}
									}
									loc: Object {
										filename: "typescript/declare/destructure-new-line/input.ts"
										end: Object {
											column: 12
											index: 20
											line: 2
										}
										start: Object {
											column: 11
											index: 19
											line: 2
										}
									}
								}
							]
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/declare/destructure-new-line/input.ts"
									end: Object {
										column: 40
										index: 48
										line: 2
									}
									start: Object {
										column: 6
										index: 14
										line: 2
									}
								}
								typeAnnotation: TSObjectTypeAnnotation {
									loc: Object {
										filename: "typescript/declare/destructure-new-line/input.ts"
										end: Object {
											column: 40
											index: 48
											line: 2
										}
										start: Object {
											column: 16
											index: 24
											line: 2
										}
									}
									members: Array [
										TSPropertySignature {
											key: JSStaticPropertyKey {
												value: JSIdentifier {
													name: "x"
													loc: Object {
														filename: "typescript/declare/destructure-new-line/input.ts"
														identifierName: "x"
														end: Object {
															column: 19
															index: 27
															line: 2
														}
														start: Object {
															column: 18
															index: 26
															line: 2
														}
													}
												}
												loc: Object {
													filename: "typescript/declare/destructure-new-line/input.ts"
													end: Object {
														column: 19
														index: 27
														line: 2
													}
													start: Object {
														column: 18
														index: 26
														line: 2
													}
												}
											}
											optional: false
											readonly: false
											loc: Object {
												filename: "typescript/declare/destructure-new-line/input.ts"
												end: Object {
													column: 28
													index: 36
													line: 2
												}
												start: Object {
													column: 18
													index: 26
													line: 2
												}
											}
											typeAnnotation: TSNumberKeywordTypeAnnotation {
												loc: Object {
													filename: "typescript/declare/destructure-new-line/input.ts"
													end: Object {
														column: 27
														index: 35
														line: 2
													}
													start: Object {
														column: 21
														index: 29
														line: 2
													}
												}
											}
										}
										TSPropertySignature {
											key: JSStaticPropertyKey {
												value: JSIdentifier {
													name: "y"
													loc: Object {
														filename: "typescript/declare/destructure-new-line/input.ts"
														identifierName: "y"
														end: Object {
															column: 30
															index: 38
															line: 2
														}
														start: Object {
															column: 29
															index: 37
															line: 2
														}
													}
												}
												loc: Object {
													filename: "typescript/declare/destructure-new-line/input.ts"
													end: Object {
														column: 30
														index: 38
														line: 2
													}
													start: Object {
														column: 29
														index: 37
														line: 2
													}
												}
											}
											optional: false
											readonly: false
											loc: Object {
												filename: "typescript/declare/destructure-new-line/input.ts"
												end: Object {
													column: 38
													index: 46
													line: 2
												}
												start: Object {
													column: 29
													index: 37
													line: 2
												}
											}
											typeAnnotation: TSNumberKeywordTypeAnnotation {
												loc: Object {
													filename: "typescript/declare/destructure-new-line/input.ts"
													end: Object {
														column: 38
														index: 46
														line: 2
													}
													start: Object {
														column: 32
														index: 40
														line: 2
													}
												}
											}
										}
									]
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/declare/destructure-new-line/input.ts"
							end: Object {
								column: 40
								index: 48
								line: 2
							}
							start: Object {
								column: 6
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
```

### `diagnostics`

```
✔ No known problems!

```