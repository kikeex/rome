# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 341`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 23
			index: 23
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "js-parser"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Unexpected token, expected {"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceType: "script"
				end: Object {
					column: 21
					index: 21
					line: 1
				}
				start: Object {
					column: 19
					index: 19
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 23
					index: 23
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 23
						index: 23
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				left: JSAssignmentIdentifier {
					name: "x"
					loc: Object {
						filename: "input.js"
						identifierName: "x"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				right: JSObjectExpression {
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 23
							index: 23
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
					properties: Array [
						JSObjectMethod {
							kind: "get"
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "method"
									loc: Object {
										filename: "input.js"
										identifierName: "method"
										end: Object {
											column: 16
											index: 16
											line: 1
										}
										start: Object {
											column: 10
											index: 10
											line: 1
										}
									}
								}
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 16
										index: 16
										line: 1
									}
									start: Object {
										column: 10
										index: 10
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 23
									index: 23
									line: 1
								}
								start: Object {
									column: 6
									index: 6
									line: 1
								}
							}
							head: JSFunctionHead {
								async: false
								generator: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								typeParameters: undefined
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 18
										index: 18
										line: 1
									}
									start: Object {
										column: 16
										index: 16
										line: 1
									}
								}
							}
							body: JSBlockStatement {
								directives: Array []
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 23
										index: 23
										line: 1
									}
									start: Object {
										column: 19
										index: 19
										line: 1
									}
								}
								body: Array [
									JSExpressionStatement {
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 21
												index: 21
												line: 1
											}
											start: Object {
												column: 19
												index: 19
												line: 1
											}
										}
										expression: JSNumericLiteral {
											value: 42
											format: undefined
											loc: Object {
												filename: "input.js"
												end: Object {
													column: 21
													index: 21
													line: 1
												}
												start: Object {
													column: 19
													index: 19
													line: 1
												}
											}
										}
									}
								]
							}
						}
					]
				}
			}
		}
	]
}
```
