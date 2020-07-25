# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > modifiers-properties`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/modifiers-properties/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/modifiers-properties/input.ts"
		end: Object {
			column: 0
			index: 397
			line: 22
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "typescript/class/modifiers-properties/input.ts"
					identifierName: "C"
					end: Object {
						column: 16
						index: 16
						line: 1
					}
					start: Object {
						column: 15
						index: 15
						line: 1
					}
				}
			}
			abstract: true
			loc: Object {
				filename: "typescript/class/modifiers-properties/input.ts"
				end: Object {
					column: 1
					index: 396
					line: 21
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/modifiers-properties/input.ts"
					end: Object {
						column: 1
						index: 396
						line: 21
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "r"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "r"
									end: Object {
										column: 14
										index: 33
										line: 2
									}
									start: Object {
										column: 13
										index: 32
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 33
									line: 2
								}
								start: Object {
									column: 13
									index: 32
									line: 2
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 15
								index: 34
								line: 2
							}
							start: Object {
								column: 4
								index: 23
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 23
								line: 2
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 33
									line: 2
								}
								start: Object {
									column: 4
									index: 23
									line: 2
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "r2"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "r2"
									end: Object {
										column: 15
										index: 50
										line: 3
									}
									start: Object {
										column: 13
										index: 48
										line: 3
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 15
									index: 50
									line: 3
								}
								start: Object {
									column: 13
									index: 48
									line: 3
								}
							}
						}
						value: undefined
						definite: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 25
								index: 60
								line: 3
							}
							start: Object {
								column: 4
								index: 39
								line: 3
							}
						}
						typeAnnotation: TSNumberKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 24
									index: 59
									line: 3
								}
								start: Object {
									column: 18
									index: 53
									line: 3
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: true
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 39
								line: 3
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 16
									index: 51
									line: 3
								}
								start: Object {
									column: 4
									index: 39
									line: 3
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "a"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "a"
									end: Object {
										column: 14
										index: 75
										line: 4
									}
									start: Object {
										column: 13
										index: 74
										line: 4
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 75
									line: 4
								}
								start: Object {
									column: 13
									index: 74
									line: 4
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 15
								index: 76
								line: 4
							}
							start: Object {
								column: 4
								index: 65
								line: 4
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 65
								line: 4
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 75
									line: 4
								}
								start: Object {
									column: 4
									index: 65
									line: 4
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "s"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "s"
									end: Object {
										column: 12
										index: 89
										line: 5
									}
									start: Object {
										column: 11
										index: 88
										line: 5
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 12
									index: 89
									line: 5
								}
								start: Object {
									column: 11
									index: 88
									line: 5
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 13
								index: 90
								line: 5
							}
							start: Object {
								column: 4
								index: 81
								line: 5
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 81
								line: 5
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 12
									index: 89
									line: 5
								}
								start: Object {
									column: 4
									index: 81
									line: 5
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pu"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pu"
									end: Object {
										column: 13
										index: 105
										line: 7
									}
									start: Object {
										column: 11
										index: 103
										line: 7
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 13
									index: 105
									line: 7
								}
								start: Object {
									column: 11
									index: 103
									line: 7
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 14
								index: 106
								line: 7
							}
							start: Object {
								column: 4
								index: 96
								line: 7
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "public"
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 96
								line: 7
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 13
									index: 105
									line: 7
								}
								start: Object {
									column: 4
									index: 96
									line: 7
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "po"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "po"
									end: Object {
										column: 16
										index: 123
										line: 8
									}
									start: Object {
										column: 14
										index: 121
										line: 8
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 16
									index: 123
									line: 8
								}
								start: Object {
									column: 14
									index: 121
									line: 8
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 17
								index: 124
								line: 8
							}
							start: Object {
								column: 4
								index: 111
								line: 8
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "protected"
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 111
								line: 8
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 16
									index: 123
									line: 8
								}
								start: Object {
									column: 4
									index: 111
									line: 8
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pi"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pi"
									end: Object {
										column: 14
										index: 139
										line: 9
									}
									start: Object {
										column: 12
										index: 137
										line: 9
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 139
									line: 9
								}
								start: Object {
									column: 12
									index: 137
									line: 9
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 15
								index: 140
								line: 9
							}
							start: Object {
								column: 4
								index: 129
								line: 9
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "private"
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 129
								line: 9
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 14
									index: 139
									line: 9
								}
								start: Object {
									column: 4
									index: 129
									line: 9
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "ra"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "ra"
									end: Object {
										column: 24
										index: 166
										line: 11
									}
									start: Object {
										column: 22
										index: 164
										line: 11
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 24
									index: 166
									line: 11
								}
								start: Object {
									column: 22
									index: 164
									line: 11
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 25
								index: 167
								line: 11
							}
							start: Object {
								column: 4
								index: 146
								line: 11
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: undefined
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 146
								line: 11
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 24
									index: 166
									line: 11
								}
								start: Object {
									column: 4
									index: 146
									line: 11
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "ar"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "ar"
									end: Object {
										column: 24
										index: 192
										line: 12
									}
									start: Object {
										column: 22
										index: 190
										line: 12
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 24
									index: 192
									line: 12
								}
								start: Object {
									column: 22
									index: 190
									line: 12
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 25
								index: 193
								line: 12
							}
							start: Object {
								column: 4
								index: 172
								line: 12
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: undefined
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 172
								line: 12
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 24
									index: 192
									line: 12
								}
								start: Object {
									column: 4
									index: 172
									line: 12
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "sr"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "sr"
									end: Object {
										column: 22
										index: 216
										line: 13
									}
									start: Object {
										column: 20
										index: 214
										line: 13
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 22
									index: 216
									line: 13
								}
								start: Object {
									column: 20
									index: 214
									line: 13
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 23
								index: 217
								line: 13
							}
							start: Object {
								column: 4
								index: 198
								line: 13
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: true
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 198
								line: 13
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 22
									index: 216
									line: 13
								}
								start: Object {
									column: 4
									index: 198
									line: 13
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pur"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pur"
									end: Object {
										column: 23
										index: 242
										line: 15
									}
									start: Object {
										column: 20
										index: 239
										line: 15
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 23
									index: 242
									line: 15
								}
								start: Object {
									column: 20
									index: 239
									line: 15
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 24
								index: 243
								line: 15
							}
							start: Object {
								column: 4
								index: 223
								line: 15
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "public"
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 223
								line: 15
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 23
									index: 242
									line: 15
								}
								start: Object {
									column: 4
									index: 223
									line: 15
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pua"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pua"
									end: Object {
										column: 23
										index: 267
										line: 16
									}
									start: Object {
										column: 20
										index: 264
										line: 16
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 23
									index: 267
									line: 16
								}
								start: Object {
									column: 20
									index: 264
									line: 16
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 24
								index: 268
								line: 16
							}
							start: Object {
								column: 4
								index: 248
								line: 16
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: "public"
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 248
								line: 16
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 23
									index: 267
									line: 16
								}
								start: Object {
									column: 4
									index: 248
									line: 16
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pus"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pus"
									end: Object {
										column: 21
										index: 290
										line: 17
									}
									start: Object {
										column: 18
										index: 287
										line: 17
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 21
									index: 290
									line: 17
								}
								start: Object {
									column: 18
									index: 287
									line: 17
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 22
								index: 291
								line: 17
							}
							start: Object {
								column: 4
								index: 273
								line: 17
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "public"
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 273
								line: 17
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 21
									index: 290
									line: 17
								}
								start: Object {
									column: 4
									index: 273
									line: 17
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pura"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pura"
									end: Object {
										column: 33
										index: 325
										line: 18
									}
									start: Object {
										column: 29
										index: 321
										line: 18
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 33
									index: 325
									line: 18
								}
								start: Object {
									column: 29
									index: 321
									line: 18
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 34
								index: 326
								line: 18
							}
							start: Object {
								column: 4
								index: 296
								line: 18
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: "public"
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 296
								line: 18
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 33
									index: 325
									line: 18
								}
								start: Object {
									column: 4
									index: 296
									line: 18
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "puar"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "puar"
									end: Object {
										column: 33
										index: 360
										line: 19
									}
									start: Object {
										column: 29
										index: 356
										line: 19
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 33
									index: 360
									line: 19
								}
								start: Object {
									column: 29
									index: 356
									line: 19
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 34
								index: 361
								line: 19
							}
							start: Object {
								column: 4
								index: 331
								line: 19
							}
						}
						meta: JSClassPropertyMeta {
							abstract: true
							accessibility: "public"
							optional: false
							readonly: true
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 331
								line: 19
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 33
									index: 360
									line: 19
								}
								start: Object {
									column: 4
									index: 331
									line: 19
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "pusr"
								loc: Object {
									filename: "typescript/class/modifiers-properties/input.ts"
									identifierName: "pusr"
									end: Object {
										column: 31
										index: 393
										line: 20
									}
									start: Object {
										column: 27
										index: 389
										line: 20
									}
								}
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 31
									index: 393
									line: 20
								}
								start: Object {
									column: 27
									index: 389
									line: 20
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/modifiers-properties/input.ts"
							end: Object {
								column: 32
								index: 394
								line: 20
							}
							start: Object {
								column: 4
								index: 366
								line: 20
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: "public"
							optional: false
							readonly: true
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 4
								index: 366
								line: 20
							}
							loc: Object {
								filename: "typescript/class/modifiers-properties/input.ts"
								end: Object {
									column: 31
									index: 393
									line: 20
								}
								start: Object {
									column: 4
									index: 366
									line: 20
								}
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