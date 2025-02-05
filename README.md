# replaceJames
To replace James Dong

Version 1: <br>
查数 <br>
context：文件里一个value associated property (ex. repository, revenue, EBIT, etc) 会在不同的section和chart里反复出现，数字可能是罗马数字或者spelled out，工作内容之一是每个property每改一次数字就manually找所有property相关的内容并确保数字改对了 <br>
goal: <br>
1. given document，确保每个property的相应数字都consistent <br>
2. 每次property改数字的时候，自动把所有相关数字改了 <br>
形势：最终做出类似一个extension的东西在word/google docs上能用 <br>
    第一步先在colab上insert document

Version x:
生成info book <br>
goal: given公司名字，生成info book，包括industry overview, competitive advantage, company overview, company's financial information <br>
难点: <br>
1. security：公司不愿意放ai在工作电脑上
2. 需要customize：修饰data （competitive advantage要找到公司领先的field，fi率先display好的data等）<br>
competitive advantage over chatgpt：<br>
1. chatgpt会编数据/编内容，我们可以做爬虫，确保不会瞎编 <br>
2. chatgpt内容重复，一多容易内容空洞没法用，我们可以specifically train招股书，确保这个写招股书格式内容usable <br>
