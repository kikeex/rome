# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 491`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 39
      index: 39
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
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'package is a reserved word'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 17
          index: 17
          line: 1
        }
        start: Object {
          column: 10
          index: 10
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 39
          index: 39
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: CallExpression {
        arguments: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 39
            index: 39
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        callee: FunctionExpression {
          id: BindingIdentifier {
            name: 'package'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 17
                index: 17
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
            filename: 'input.js'
            end: Object {
              column: 36
              index: 36
              line: 1
            }
            start: Object {
              column: 1
              index: 1
              line: 1
            }
          }
          head: FunctionHead {
            async: false
            generator: false
            hasHoistedVars: false
            params: Array []
            predicate: undefined
            rest: undefined
            returnType: undefined
            thisType: undefined
            typeParameters: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 17
                index: 17
                line: 1
              }
            }
          }
          body: BlockStatement {
            body: Array []
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 36
                index: 36
                line: 1
              }
              start: Object {
                column: 20
                index: 20
                line: 1
              }
            }
            directives: Array [
              Directive {
                value: 'use strict'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                  start: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                }
              }
            ]
          }
        }
      }
    }
  ]
}
```