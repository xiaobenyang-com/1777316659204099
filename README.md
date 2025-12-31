# 计算器服务器 

一个功能完整的基于 Model Context Protocol (MCP) 的计算器服务器，提供丰富的数学运算功能，包括基础算术、根式运算、三角函数、对数运算、统计学、组合数学、数论、复数运算、矩阵运算、数值分析、金融计算、单位转换和几何计算等 13 个专业数学模块。
A fully functional calculator server based on Model Context Protocol (MCP), providing rich mathematical operation functions It includes 13 specialized mathematics modules such as basic arithmetic, radical operations, trigonometric functions, logarithmic operations, statistics, combinatorial mathematics, number theory, complex number operations, matrix operations, numerical analysis, financial computing, unit conversion and geometric computing.## 工具列表 Tool List

本MCP服务封装下列工具，可让模型通过标准化接口调用以下功能。 本MCP服务封装下列工具，可让模型通过标准化接口调用以下功能。

| 工具 Tool   | 描述 Description         |
|-------|--------------------|
| add | 执行两个数字的加法运算 |
| subtract | 执行两个数字的减法运算 |
| multiply | 执行两个数字的乘法运算 |
| divide | 执行两个数字的除法运算 |
| modulo | 计算两个数的余数 |
| power | 计算a的b次方 |
| sqrt | 计算数字的平方根 |
| cbrt | 计算数字的立方根 |
| nthRoot | 计算数字的n次方根 |
| abs | 计算数字的绝对值 |
| sin | 计算角度的正弦值（输入为弧度） |
| cos | 计算角度的余弦值（输入为弧度） |
| tan | 计算角度的正切值（输入为弧度） |
| asin | 计算反正弦值（返回弧度） |
| acos | 计算反余弦值（返回弧度） |
| atan | 计算反正切值（返回弧度） |
| atan2 | 计算从x轴到点(x,y)的角度（返回弧度） |
| sinh | 计算双曲正弦值 |
| cosh | 计算双曲余弦值 |
| tanh | 计算双曲正切值 |
| asinh | 计算反双曲正弦值 |
| acosh | 计算反双曲余弦值（输入值必须≥1） |
| atanh | 计算反双曲正切值（输入值必须在-1到1之间） |
| sec | 计算正割值（1/cos） |
| csc | 计算余割值（1/sin） |
| cot | 计算余切值（1/tan） |
| degToRad | 将角度转换为弧度 |
| radToDeg | 将弧度转换为角度 |
| ln | 计算自然对数（以e为底） |
| log10 | 计算以10为底的对数 |
| log | 计算以指定底数的对数 |
| mean | 计算数组的算术平均值 |
| median | 计算数组的中位数 |
| mode | 计算数组的众数（出现频率最高的数） |
| stdDev | 计算数组的标准差 |
| variance | 计算数组的方差 |
| max | 找出数组中的最大值 |
| min | 找出数组中的最小值 |
| sum | 计算数组所有元素的和 |
| product | 计算数组所有元素的乘积 |
| range | 计算数组的范围（最大值-最小值） |
| factorial | 计算非负整数的阶乘 |
| permutation | 计算从n个元素中选择r个元素的排列数 P(n,r) |
| combination | 计算从n个元素中选择r个元素的组合数 C(n,r) |
| fibonacci | 计算斐波那契数列的第n项 |
| fibonacciSequence | 生成斐波那契数列的前n项 |
| catalan | 计算第n个卡塔兰数 |
| bellNumber | 计算第n个贝尔数（集合划分数） |
| binomialCoefficient | 计算二项式系数 (n choose k) |
| gcd | 计算两个或多个整数的最大公约数 |
| lcm | 计算两个或多个整数的最小公倍数 |
| isPrime | 判断一个正整数是否为素数 |
| primeFactorization | 将正整数分解为素因数的乘积 |
| eulerPhi | 计算欧拉函数φ(n)，即小于等于n且与n互质的正整数个数 |
| isPerfectNumber | 判断一个正整数是否为完全数（等于其所有真因子之和） |
| divisorCount | 计算正整数的因子个数 |
| divisorList | 列出正整数的所有因子 |
| complex_add | 计算两个复数的和 |
| complex_subtract | 计算两个复数的差 |
| complex_multiply | 计算两个复数的乘积 |
| complex_divide | 计算两个复数的商 |
| complex_magnitude | 计算复数的模长（绝对值） |
| complex_conjugate | 计算复数的共轭 |
| complex_argument | 计算复数的幅角（以弧度为单位） |
| complex_polar | 将复数转换为极坐标形式 r∠θ |
| matrix_add | 计算两个矩阵的和 |
| matrix_subtract | 计算两个矩阵的差 |
| matrix_multiply | 计算两个矩阵的乘积 |
| matrix_transpose | 计算矩阵的转置 |
| matrix_determinant | 计算方阵的行列式 |
| matrix_inverse | 计算方阵的逆矩阵 |
| matrix_trace | 计算方阵的迹（对角线元素之和） |
| numerical_integration | 使用梯形法则计算函数的定积分 |
| numerical_derivative | 使用中心差分法计算函数在某点的导数 |
| newton_method | 使用牛顿法求解方程的根 |
| bisection_method | 使用二分法求解方程在区间内的根 |
| lagrange_interpolation | 使用拉格朗日插值法计算插值点的函数值 |
| compound_interest | 计算复利投资的未来价值 |
| present_value_annuity | 计算普通年金的现值 |
| future_value_annuity | 计算普通年金的未来值 |
| loan_payment | 计算等额本息贷款的月供金额 |
| net_present_value | 计算投资项目的净现值（NPV） |
| internal_rate_of_return | 计算投资项目的内部收益率（IRR） |
| bond_price | 计算债券的理论价格 |
| length_conversion | 在不同长度单位之间进行转换 |
| weight_conversion | 在不同重量单位之间进行转换 |
| temperature_conversion | 在摄氏度、华氏度和开尔文之间进行转换 |
| area_conversion | 在不同面积单位之间进行转换 |
| volume_conversion | 在不同体积单位之间进行转换 |
| time_conversion | 在不同时间单位之间进行转换 |
| speed_conversion | 在不同速度单位之间进行转换 |
| circle_calculation | 计算圆的面积、周长等属性 |
| rectangle_calculation | 计算矩形的面积、周长等属性 |
| triangle_calculation | 根据三边长计算三角形的面积、周长等属性 |
| trapezoid_calculation | 计算梯形的面积 |
| ellipse_calculation | 计算椭圆的面积和周长（近似） |
| sphere_calculation | 计算球体的体积和表面积 |
| cylinder_calculation | 计算圆柱体的体积和表面积 |
| cone_calculation | 计算圆锥体的体积和表面积 |
| cuboid_calculation | 计算长方体的体积和表面积 |
| regular_polygon | 计算正多边形的面积和周长 |


## 检查服务 ## Inspector

工具在线测试： [https://mcp.xiaobenyang.com/inspector/1777316659204099](https://mcp.xiaobenyang.com/inspector/1777316659204099)

Online Tool test [https://mcp.xiaobenyang.com/inspector/1777316659204099](https://mcp.xiaobenyang.com/inspector/1777316659204099)

## 服务配置 MCP Server Config


> #### 如何获取 XBY-APIKEY ？ How to get XBY-APIKEY ?
> 访问小笨羊科技网站 [https://xiaobenyang.com](https://xiaobenyang.com)，注册用户即可获得APIKEY
> Visit XiaoBenYang website [https://xiaobenyang.com](https://xiaobenyang.com), register and get the APIKEY.

### SSE
```json
{
  "mcpServers": {
    "计算器服务器": {
      "headers": {
        "XBY-APIKEY": "<YOUR_XBY_APIKEY>"
      },
      "type": "sse",
      "url": "https://mcp.xiaobenyang.com/1777316659204099/sse"
    }
  }
}
```
### STREAMABLE HTTP
```json
{
  "mcpServers": {
    "计算器服务器": {
      "headers": {
        "XBY-APIKEY": "<YOUR_XBY_APIKEY>"
      },
      "type": "streamable_http",
      "url": "https://mcp.xiaobenyang.com/1777316659204099/mcp"
    }
  }
}
```
### STDIO
```json
{
    "mcpServers": {
        "计算器服务器": {
          "command": "npx",
          "args": [
            "-y",
            "xiaobenyang-mcp"
          ],
          "env": {
            "XBY_APIKEY": "<YOUR_XBY_APIKEY>",
            "mcpId": "1777316659204099",
          },
          "transport": "stdio"
        }
      }
}

```
