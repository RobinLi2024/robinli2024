### Hi there 👋
<kbd>![motorhome 3](https://github.com/RobinLi2024/robinli2024/assets/170358474/8475902e-e754-4ce2-9a2e-d83f487b3d5c)</kbd>

<!--
**RobinLi2024/robinli2024** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Table of Contents
- [data source](#data-source)
- [calculate the fuel efficency](#calculate-the-fuel-efficency)

***

## data source

-- raw data:
      
Date Time store location distance    price/litre quantity   amount
1.  2022/09/12 18:48:18 shell 17203 hiller rd sw edmonton    $1.369   29.277      $40.08
2.  2022/09/12 18:53:20 shell  17203 hiller rd sw edmonton   $1.369   27.200      $37.24
3.  2022/08/23 4:15 pm pat's waterton park n/a  n/a $17.10
4.  2022/08/23 14:40:47 pat's waterton park 244 mountainview rd waterton park n/a n/a $191.77
5.  2022/08/22 13:20:40 costco 99 heritage gate se calgary $1.359 53.799 $73.11
6.  2022/08/22 13:42:19 costco 99 heritage gate se calgary $1.359 43.503 $59.12
7.  2022/08/24 11:55:57 shell 4312 1st street claresholm $1.399 28.592 $40.00
8.  2022/08/25 11:35:06 costco 11588 sarcee trail nw calgary $1.349 54.136 $73.03
9.  2022/8/24 10:45:55 shell 1330 wentworth ave pincher creek $1.479 14.467 $21.40



## calculate the fuel efficency

**Step 1: Data cleaning.**
1. Converted date time columns into datetime format. Sort the data by date.
2. fill the distance manually (trip starting from Edmonton)
<kbd>![image](https://github.com/RobinLi2024/robinli2024/assets/170358474/5d3c3745-9c54-4f39-bb9c-d537c75cf422)</kbd>

**Step 2: Data analytics.**

formular:
    total of fuel / total of distance

  ```29.93```L per 100 KM

  <kbd>![image](https://github.com/RobinLi2024/robinli2024/assets/170358474/f0a22958-9f4c-4298-8d2e-ee42594ed808)</kbd>

💥notes: The milage should be better, as I did not includes many small trips. Espcially the one in Waterton, where I drove this big guy into the mountain looking for the Cameron Fall. I gave up after drove for about half hour in afraid of not having enough fuel. It turns out that the Cameron Fall is inside Waterton town! The road into the mountain has a lot of hills up and down. At one of the hill I almost hit another car, as I did not slow down when I reach the top the hill...
