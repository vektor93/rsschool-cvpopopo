Victoria Onischuk
=================
### My Contact Info ###
+ Phone: +375336657280
+ Telegram: @vektor_93
+ e-mail: blablablayn93@gmail.com
----------------------
### Briefly About Myself: ###
At the moment I am studying in a technical specialty, and I always have been interested in everything related to mathematics and physics. During my studies, I constantly learn programming. I realized that I was interested in this area and I want to develop in it. I decided to try myself as a Frontend Developer, because this area is closest to me. I also like working with images, editing them, etc. I have good skills in Photoshop and various mobile applications related to image processing. I am ready to spend and at the moment I am spending my free time to learn something new. I sincerely believe that the field of programming allows you to constantly develop and improve. 

I believe that my drive to learn and acquire quality skills will enable me to become proficient Frontend Developer.
### My strengths: ### 
+ responsibility
+ communication skills
------------------------
### Skills and Proficiency: ###
+ HTML
+ C++ , Python, Matlab
+ JavaScript (basics)
+ Figma
+ AdobePhotoshop
+ Git, GitHub
-------------------------
### Code example: ###

```c#
using System;

namespace Task2
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Введите число: ");
            int chilso = int.Parse(Console.ReadLine());  // число в десятичной
            Console.WriteLine("Введите основание: ");
            int osnovanie = int.Parse(Console.ReadLine());  // основание числа
            string result = "";     // переменная для результата
            int temp = 0;
            Console.WriteLine("Число в 10-ой системе = " + chilso);

            if (chilso > 0)     // условие, что число больше 0
                while (chilso >= (osnovanie - 1))   // пока число больше самого основания
                {
                    temp = chilso % osnovanie;
                    chilso = (chilso - temp) / osnovanie;
                    result = Convert.ToString(temp) + result;
                }
            result = Convert.ToString(chilso) + result;
            Console.WriteLine("Число в " + osnovanie + "-ой системе = " + result);
        }
    }
} 
```
---------------------------------
### Education
Bachelor, Belarusian State University, Faculty of Radiophysics and Computer Technologies, Minsk

-------------------
### Languages ###
+ Russian
+ Belarusian
+ Ukrainian
+ English (A2-B1)

Language experience:

Volunteer at the II European Games (services for viewers).
