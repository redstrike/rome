# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > trailing-function-commas > 1`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
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
      column: 16
      index: 16
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 16
          index: 16
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: CallExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        callee: ReferenceIdentifier {
          name: 'log'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 3
              index: 3
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        arguments: Array [
          ReferenceIdentifier {
            name: 'n'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 5
                index: 5
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
          }
          StringLiteral {
            value: '='
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 10
                index: 10
                line: 1
              }
              start: Object {
                column: 7
                index: 7
                line: 1
              }
            }
          }
          NumericLiteral {
            value: 2
            format: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 13
                index: 13
                line: 1
              }
              start: Object {
                column: 12
                index: 12
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```