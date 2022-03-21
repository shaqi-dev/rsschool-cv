# Vladislav Zubakin
## Junior Frontend Developer
## Contacts
- **Phone:** +375 (33) 329-67-19
- **E-mail:** shaqimusic@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/vladislavzubakin
- **GitHub:** https://github.com/Shaqi-dev
- **Telegram:** [@shaaqi](https://t.me/shaaaqi)
- **Skype:** live:c202c05811a8a042
## About Me
I'm a Junior Front-end developer from Belarus with a passion for learning and innovating.
My first website, which I even managed to sell, I made at a very young age (about 10-12 years old). It was a site on the platform uCoz, the theme of the site - a series of games "Counter-Strike", namely the various add-ons to them.
At the moment I am fully learning modern Front-end development, and looking for my first job.
In my free time, I mostly trade cryptocurrencies, make music, and play computer games with my friends.
- **My strengths:**
- - Fast learner
- - Teamwork
- - Attention to detail
## Skills
- **Mark-up:** HTML5, CSS3, BEM, Sass, Bootstrap
- **JavaScript:** Vanilla JS, ES6, JQuery
- **Framework:** React JS + Redux
- **Tools:** Gulp, Webpack, Git/GitHub, Figma/Photoshop
# Code Example
**Write Number in Expanded Form:** You will be given a number and you will need to return it as a string in Expanded Form.
```
function expandedForm(num) {
    if (isNaN(num)) return NaN;
    
    let digits = num.toString().split(''),
        result = [];
    
    digits.forEach((digit, i) => { 
        if (digit > 0) result.push(digit * (10 ** (digits.length - i - 1)))
    });

    return result.join(' + ');
}
```
