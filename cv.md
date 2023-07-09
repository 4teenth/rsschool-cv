# Andrii Ovsiannikov

### Contact:

**Location:** Dnipro, Ukraine<br>
**Phone:** +380660422440<br>
**Email:** aio.ao91@gmail.com<br>
**Telegram:** @andplusrew<br>
**Skype:** live:aio.ao91<br>
[Github](https://bit.ly/3rfkO7s)<br>
[LinkedIn](https://bit.ly/4021MTF)

### Summary:

During the last year, I've learned technologies in Front-End Web Development and gathered new
experience.<br>
Took part in some training programs and courses. I am open for getting new experience and knowledge,<br>
I always try to understand the essence of the issue and never give up.

### Technical skills:

- **Technologies:** HTML5, CSS3, JavaScript;
- **Related technologies\notions:** Responsive web design, Pixel Perfect, Flexbox/Grid, CSS pre-\postprocessors Sass/Less\Autoprefixer, lazysizes/lodash libs, Bootstrap;
- **Methodologies:** Agile, Scrum, BEM(web dev);
- **Development tools:** VSC, Github/Gitlab, Gulp Kit, Webpack, Bourbon;

### Code example:

**Find the perimeter of the square:**

```
function perimetr(matrix) {
  let p = 0;
  for (let i = 0; i < matrix.length; i += 1) {
    for (let j = 0; j < matrix[i].length; j++) {
      if (matrix[i][j] === "X") {
        p += j === 0 || matrix[i][j - 1] === "O";
        p += i === 0 || matrix[i - 1][j] === "O";
        p += i === matrix.length - 1 || matrix[i + 1][j] === "O";
        p += j === matrix[i].length - 1 || matrix[i][j + 1] === "O";
      }
    }
  }
  return p;
}
```

### Education:

- **University:** Dnipro University of Technology, _Electromechanical automation systems and electrical
  drive_
- **Courses:**
  - [GoIT](https://goit.global/ua/)
  - Epam University program

### Languages:

**English** - B1
