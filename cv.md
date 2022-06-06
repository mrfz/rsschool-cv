# Fedor Zlobin

## Contact Info

***Address:*** Russian Federation, Sochi

***E-mail:*** [zlobin.f@gmail.com](mailto:zlobin.f+github@gmail.com)

***GitHub:*** [mrfz](https://github.com/mrfz)

***CodeWars:*** [mrffz](https://www.codewars.com/users/mrffz)

***CodinGame:*** [mrffz](https://www.codingame.com/profile/c3512bfb9d2f097fe43e7ffac01f82163995543)

---

## About Me

I am 34 years old, work as Senior Service SCADA Engineer at ski resort in Sochi. Also I learn Industrial innovations at [DONSTU](https://donstu.ru/). My willing to this course is to take a first step into software development in general and front-end in particular. 

---
## Skills
+ *Advanced:* 
    - Honeywell EBI
    - Honeywell CARE
    - VBScript
    - HVAC Automation
    - SCADA systems in general
+ *Good:*  
    - MS Office, Excel Automation
    - Libre Office
    - git
+ *Basic:*
    - Python (numpy, pandas, matplotlib)
    - JavaScript
    - C#, Unity
    - IEC 1131-3

---
## Code examples
```
export const parseEnv = () => {
    let outputString = ""
    Object.entries(process.env)
        .filter(([key,value]) => key.substring(0,4) === 'RSS_')
        .map(([key,value]) => outputString = outputString.concat(`${key}=${value}; `));
    outputString !== ""  ?  console.log(outputString.slice(0,outputString.length-2)) : null;
};
parseEnv();
```

---
## Education
+ **Higher:**
  - [MISIS](misis.ru) - Mining - *not completed*
  - [MISIS](misis.ru) - Software - *not completed*
  - [DONSTU](https://donstu.ru/) - Industrial innovations - ***in progress***
+ **Courses:**
  - [soloLearn](sololearn.com) - pyhton, machine learning, C#, SQL

---
## Languages
+ Russian - Native
+ English - Advanced - I've worked with foreigners at Inmarsat
+ Ukranian - Basic

---