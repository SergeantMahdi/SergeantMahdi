<img src="./cdn/banners/BannerMatthew2.webp" alt="Main banner">

<h1 align="center">
      Hi, I'm (Matthew) Mahdi
</h1>

<p>
   I'm a 24-year-old <strong><code>Full-Stack web and C++ developer</code></strong>. As I started learning how to code in 2021 by digging into <strong><code>C++</code></strong>
   I found my way to the world of programmers. My curiosity didn't stop there and led me to the path of <strong><code>Web Development</code></strong>, since I'd already known C++ it wasn't challenging to learn syntax of <strong><code>JS</code></strong>
   , <strong><code>CSS</code></strong> and <strong><code>HTML</code></strong>
   but took me a while to get a deep understanding of how everything works.
   Web development helped me to go deeper into programming and gave me the ambition of following my childhood dream, becoming a <strong><code>Game Developer</code></strong> in the future.
</p>

<!-- Skills -->

   <h2 align="center" >My Skills</h2>
   <img src="./cdn/banners/skillsBanner.webp" alt="Skills banner"> 

   <table align="center">
      <tr>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/cpp.svg" alt="C++">
            <p align="center">
               C++
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/javascript.svg" alt="JavaScript">
            <p>
               JavaScript
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/html5.svg" alt="HTML">
            <p align="center">
               HTML
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/css.svg" alt="CSS">
            <p align="center">
               CSS
            </p>
         </td>
      </tr>
      <tr>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/expressjs.svg" alt="Express.js">
            <p align="center">
               Express.js
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/nodejs.svg" alt="Node.js">
            <p align="center">
               Node.js
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/mongodb.svg" alt="MongoDB">
            <p align="center">
               MongoDB
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/nextjs.svg" alt="Next.js">
            <p align="center">
               Next.js
            </p>
         </td>
      </tr>
      <tr>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/react.svg" alt="React.js">
            <p align="center">
               React.js
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/threejs.svg" alt="Three.js">
            <p align="center">
               Three.js
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/tailwindcss.svg" alt="Tailwind">
            <p align="center">
               Tailwind
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/vitejs.svg" alt="Vite">
            <p align="center">
               Vite
            </p>
         </td>
      </tr>
      <tr>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/figma.svg" alt="Figma">
            <p align="center">
               Figma
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/git.svg" alt="Git">
            <p align="center">
               Git
            </p>
         </td>
         <td align="center">
            <img width=80 height=80 src="./cdn/svgs/skills/github.svg" alt="GitHub">
            <p align="center">
               GitHub
            </p>
         </td>
      </tr>
   </table>


<h2 align="center">
      Social Media
</h2>

<table align="center">
   <tr >
      <td align="center">
         <a href="https://www.linkedin.com/in/mahdi-sartipzadeh/">
            <img width=80 height=80 src="./cdn/svgs/socialMedia/linkedin.svg">
            <p>Linkedin</p>
         </a>
      </td>
      <td align="center">
         <img width=80 height=80 src="./cdn/svgs/socialMedia/instagram.svg">
         <p>Instagram</p>
      </td>
      <td align="center">
         <img width=80 height=80 src="./cdn/svgs/socialMedia/youtube.svg">
         <p>Youtube</p>
      </td>
   </tr>
</table>

<p align="center">
<a href="https://git.io/streak-stats">
<img src="https://streak-stats.demolab.com?user=SergeantMahdi&theme=dark&hide_border=true&short_numbers=true&date_format=j%20M%5B%20Y%5D&mode=weekly&fire=ffa100&background=00000000&stroke=ffa100&currStreakLabel=ffa100" alt="GitHub Streak" />
</a>
<p>

```cpp
#include <string>
#include <vector>


struct User {
    std::string status;
    std::string attitude;
    bool isFailed;

    User()
       :status("Trying"), attitude("Persistent"), isFailed(false) {}
};

int main(){
     std::vector<std::string> life = {"Challenge", "Failure", "Miserableness" };
     User user;

     while(user.status == "Trying"){
         if(user.attitude == "Persistent"){
              if(life.empty())
                 life.pop_back();
              else break;
         }
         else{
             user.isFailed = true;
             break;
         }
    }
}
```
