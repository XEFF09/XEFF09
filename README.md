<div align="center">
  <img align="left" src="https://media.tenor.com/w5a0WVW1GbsAAAAd/nijika-bocchi-the-rock.gif" align="left" width="400px" height="208.5px">

  <p align="right"> <img src="https://komarev.com/ghpvc/?username=xeff09&label=Profile%20views&color=0e75b6&style=flat" alt="xeff09" /> </p>
  <br>

  <p align="center">
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> 
    </a> 
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
    </a> 
    <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
    </a> 
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> 
    </a> 
    <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
    </a> 
  </p>
  
  <p align="center">
    <a href="https://www.instagram.com/pp_u.nn/?next=%2F" target="_blank"><img src="https://img.shields.io/badge/pp_u.nn%20-%23f24f1d.svg?&style=for-the-badge&logo=Instagram&logoColor=white"/></a> 
    <a href="https://github.com/XEFF09" target="_blank"><img src="https://img.shields.io/badge/PpUn,9229%20-%237289DA.svg?&style=for-the-badge&logo=discord&logoColor=white"/></a>
  </p>
  
</div>

<br><br>

***

<table>
  <tr>
    <td align="center"><a href="https://github.com/XEFF09">< PROFILE</a></td>
    <td align="center"><a href="https://github.com/XEFF09/XEFF09/blob/main/README.md">README ></a></td>
  </tr>
  <tr>
    <td colspan="2"><img align="center" width="100%" src="https://discord-readme-badge.vercel.app/api?id=361059716891148298"><br></td>
  </tr>
</td>
  <tr>
    <th rowspan="3"><br><img align="center" width="100%" src="https://github-readme-stats.vercel.app/api?username=xeff09&show_icons=true&locale=en&theme=dark&show_icons=true"></th>
  </tr>
  <tr>
    <td align="center"><img width="100%" src="https://spotify-github-profile.vercel.app/api/view?uid=21naz3bxynvq33kljs6f3ytpy&cover_image=true&theme=natemoo-re&show_offline=true&background_color=121212&bar_color_cover=true&bar_color=53b14f"></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img align="center" width="95%" src="https://spotify-recently-played-readme.vercel.app/api?user=21naz3bxynvq33kljs6f3ytpy&count=1" alt=""></img>
    </td>
  </tr>
  <tr><th colspan="2"><img width="100%" src="https://media1.giphy.com/media/PFX8qCMjpF53bTjxLR/giphy.gif?cid=790b7611b6cb764415af623ed5d479a01edb08bc460ab7f3&rid=giphy.gif&ct=g"></th></tr>
</table>

## LAB 01

___

<details> <summary> 01 คอมพิวเตอร์ทำงาน </summary>

<br>

คอมพิวเตอร์ทำงาน จงเขียนโปรแกรมเพื่อแสดงผลเวลาที่เครื่องคอมพิวเตอร์ทำงานในรูปของจำนวนวัน ชั่วโมง และนาที ตามลำดับ (ไม่ต้องคำนึง)
เมื่อตัวแปร computer_time เก็บค่าจำนวนนาทีที่เครื่องคอมพิวเตอร์ทำงาน
    
<br>

ตัวอย่างผลลัพธ์เมื่อ computer_time มีค่า 785 
> It is 0 days 13 hours and 5 minutes.
    
อธิบาย: คอมพิวเตอร์ทำงาน 785 นาที เท่ากับ 0 วัน 13 ชั่วโมง 5 นาที

<br>
    
ตัวอย่างผลลัพธ์เมื่อ computer_time มีค่า 1678
> It is 1 days 3 hours and 58 minutes.
    
อธิบาย: คอมพิวเตอร์ทำงาน 1678 นาที เท่ากับ 1 วัน 3 ชั่วโมง 58 นาที

<br>
    
`code section`
```C
#include<stdio.h>
int main() {
    int computer_time = 785;  // ในโปรแกรมตรวจอาจเปลี่ยนค่าของตัวแปรนี้ แต่นิสิตไม่ต้องเปลี่ยนค่าของตัวแปรนี้
    
    int h = (computer_time / 60) % 24;
    int m = computer_time % 60;
    int d = (computer_time / 60 / 24);
    printf("It is %d days %d hours and %d minutes.", d, h, m);
    return 0;

    return 0;
}
```

<br>

---
</details>
    
<details> <summary> 02 Sphere Volume </summary>

<br>

จงเขียนโปรแกรมเพื่อคำนวณค่าปริมาตร (volume) ของทรงกลม ในรูปแบบทศนิยม 2 ตำแหน่ง โดยค่ารัศมี (ตัวแปร radius) เป็นจำนวนจริง
โดยใช้การคำนวณจากสูตร
    
<br>
    
$$ volume = {4 \over 3} \times {\Pi} \times {radius^3} $$
    
<br>

กำหนดค่าคงที่ 
    
$$ {\Pi} = {22 \over 7} $$
    
<br>
    
ตัวอย่างผลลัพธ์ เมื่อตัวแปร radius มีค่า 1.5
> The volume of this sphere is 14.14
    
<br>
    
`code section`
```C
#include <stdio.h>
#include <stdlib.h>

// กำหนดค่าคงที่ PI มีค่า 22.0/7
#define PI 22.0/7

int main()
{
    float radius = 1.5;
    
    float res = (4.0/3) * PI * (radius*radius*radius); 
    printf("The volume of this sphere is %.2f", res);
    return 0;

    return 0;
}
```

<br>

---
</details>

[< BACk](https://github.com/XEFF09/C-prog/tree/main/lab_md)



 





