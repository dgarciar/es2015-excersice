<!-- 
Following error when launching live server via firefox on termnial wsl2

 Error: Module build failed (from ./node_modules/babel-loader/lib/index.js):
SyntaxError: /home/daniel/first-app/src/index.js: Identifier 'fruits' has already been declared. (5:7)

�[0m �[90m 3 |�[39m�[0m
�[0m �[90m 4 |�[39m�[0m
�[0m�[31m�[1m>�[22m�[39m�[90m 5 |�[39m �[36mimport�[39m fruits �[36mfrom�[39m �[32m'./fruits'�[39m�[33m;�[39m�[0m
�[0m �[90m   |�[39m        �[31m�[1m^�[22m�[39m�[0m
�[0m �[90m 6 |�[39m �[36mimport�[39m { choice�[33m,�[39m remove } �[36mfrom�[39m �[32m'./helpers'�[39m�[33m;�[39m�[0m
�[0m �[90m 7 |�[39m�[0m
�[0m �[90m 8 |�[39m �[36mlet�[39m fruit �[33m=�[39m choice(fruits)�[33m;�[39m�[0m
    at instantiate (/home/daniel/first-app/node_modules/@babel/parser/lib/index.js:63:32)
    at constructor (/home/daniel/first-app/node_modules/@babel/parser/lib/index.js:358:12)
    at FlowParserMixin.raise (/home/daniel/first-app/node_modules/@babel/parser/lib/index.js:3255:19)
    at FlowScopeHandler.checkRedeclarationInScope (/home/daniel/first-app/node_modules/@babel/parse bundle.js:10:7
    js http://localhost:3000/static/js/bundle.js:10
    factory http://localhost:3000/static/js/bundle.js:10379
    __webpack_require__ http://localhost:3000/static/js/bundle.js:9836
    <anonymous> http://localhost:3000/static/js/bundle.js:10956
    <anonymous> http://localhost:3000/static/js/bundle.js:10958 -->