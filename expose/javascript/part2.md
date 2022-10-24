1. `3` will be printed, because `i` is function-scoped to `discountPrices()`. This means that even though the variable `i` is declared within the for-loop, it exists within the function. Additionally, `i` is updated until `i < 3` since `prices.length` is 3 (3 elements in `prices`), hence `i = 3`, and `3` is printed. <br />

2. `150` will be printed, because `var` allows for redeclarations, and for the last iteration of the for loop, `discountedPrice` is assigned to `prices[2] * (1 - 0.5)`, which is `300 * 0.5 = 150`, hence `discountedPrice` stores `150`, which is printed in line 13. <br />

3. `150` will be printed, because `finalPrice` is reassigned with each iteration, and by the last iteration, it is set to the rounded value of `discountedPrice`, which is `150`, hence `finalPrice` stores `150`, and is printed in line 14. <br />

4. `[50, 100, 150]` will be printed. `finalPrice` will be pushed onto `discounted` with each iteration, and since each of the variables are type `var`, there will be no errors. <br />

5. `error` because `i` is block-scoped, so it is not defined outside of the for-loop. Since line 12 tries print `i` there is an error. <br />

6. `error` because `discountedPrice` is block-scoped, so it is not defined outside of the for-loop. Since line 13 tries print `discountedPrice` there is an error. <br />

7. `150` will be printed, because in the last iteration, `finalPrice` is set to the rounded value of `discountedPrice`, which is `150`, hence `finalPrice` stores `150`, and is printed in line 14. `finalPrice` is defined since line 14 is called within the same block that `finalPrice` is declared. <br />

8. `[50, 100, 150]` will be printed. `finalPrice` will be pushed onto `discounted` with each iteration, and since there are no redeclarations or use of variables outside their scope, there will be no errors. <br />

9. `error` because `i` is block-scoped, so it is not defined outside of the for-loop. Since line 11 tries print `i` there is an error. <br />

10. `3` is printed because the constant `length` is assigned to `prices.length`, which is 3.
<br /> _Note: there are no errors since, there are no reassignments of `const` within the same block-scope. `discounted` is also not reassigned, just modified._ <br />

11. `[50, 100, 150]` is returned because `discount` is updated with `discountedPrices`, which is each element of `prices` multiplied by `(1 - discount)`, i.e., halving the prices. 
<br /> _Note: there are no errors since, there are no reassignments of `const` within the same block-scope. `discounted` is also not reassigned, just modified._ <br />

12. A) `student.name` <br /> 
    B) `student['Grad Year']` <br />
    C) `student.greeting()` <br />
    D) `student['Favorite Teacher'].name` <br />
    E) `student.courseLoad[0]` <br />

13. A) `'32'`: A string added to a number results in a concat
    <br />
    B) `1`: Only numbers can be subtracted, so the result is a number <br />
    C) `3`: Since `3` is a number, `null` becomes 0 <br />
    D) `'3null'`: Since `'3'` is a string, `null` becomes the stirng, `'null'` <br />
    E) `4`: Since `3` is a number, `true` is converted to `1` <br />
    F) `0`: Both `false` and `null` will be converted to `numeric` types <br />
    G) `'3undefined'`: Since `'3'` is a string, `undefined` becomes the string, `'undefined'` <br />
    H) `NaN`: The subtraction converts both `'3'` and `undefined` to their numeric values, `3` and `NaN` <br />

14. A) `true`: `'2'` is converted to the numeric value since 
    `1` is a numeric value <br />
    B) `false`: Since both `'2'` and `'12'` are strings, their characters are compared <br />
    C) `true`: `'2'` is converted to the numeric value `2` <br/>
    D) `false`: `2` and `'2'` are different types <br />
    E) `false`: `true` is converted to `1` 
    F) `true`: `Boolean(2)` is `true` since `2` is not empty and both `true` and `Boolean(2)` are Boolean types

15. `==` tries to convert types to be the same before comparing values, while `===` compares both type then value, i.e., if the types don't match, then the value is `false`.

16. in [part2-question16.js](part2-question16.js)

17. `[2,4,6]`: First `modifyArray` is called, where `newArr` is initialized. Then for each element in `array`, the element is multiplied by `2` and pushed on to `newArr`. Then, `newArr` is returned. <br />

18. in [part2-question18.js](part2-question18.js)

19. `1` <br /> `4` <br /> `3` <br /> `2`