# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 364`

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
			column: 2
			index: 2
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
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Unterminated regular expression"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceType: "script"
				end: Object {
					column: 1
					index: 1
					line: 1
				}
				start: Object {
					column: 1
					index: 1
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
					column: 2
					index: 2
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSRegExpLiteral {
				global: false
				insensitive: false
				multiline: false
				noDotNewline: false
				sticky: false
				unicode: false
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 2
						index: 2
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				expression: JSRegExpSubExpression {
					body: Array []
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
				}
			}
		}
	]
}
```
