1. **`values added: 20`** <br />
    `result` is both declared and assigned, first to `0`, then to 10+10, which is `20`, because `add` is `true`.<br /><br />
2. **`final result: 20`** <br />
    Since `add` is `true`, the if-statement is entered, and `result` is set to `20`. `result` is also declared in the function, hence `result` is `20` at line 13.<br /><br />
3. **`values added: 20`** <br />
    `result` is declared and assigned in the if-block. Since it's assigned to `20` and line 9 is in the block, `values added: 20` is printed.<br /><br />
4. **`error`** <br />
    `result` is only declared and assigned in the if-block and since line 13 is outside this block, `result` is undeclared, hence an error is returned.<br /><br />
5.  **`error`** <br />
    Since the constant `result` is being reassigned, a error will be returned.<br /><br />
6.  **`error`** <br />
    Since the constant `result` is being reassigned, a error will be returned.