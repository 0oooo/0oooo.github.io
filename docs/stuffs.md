# 08 Septembre 2022

This [article](https://javascript.plainenglish.io/its-2022-please-don-t-just-use-console-log-anymore-217638337c7d) made me want to try to improve my console logging. 
- Use an object to have more details info about what you are logging `console.log({age, name, food, paint})` will give you the name of the variables and the value you are printing!
- Using warn or error will show in the console so if you have a lot of logs and want to get the attention: `console.warn()` or `console.error()` 
- Something I never had to think about, but if I wanted to get the interval of time for the execution of some code? ```
- console.time()
for (let i = 0; i < 1000000000; i++) {
  count++
}
console.timeEnd()
```
- And finally if you have a big object to log? `console.table()` makes it pretteeeeh
