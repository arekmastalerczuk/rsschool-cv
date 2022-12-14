# Arkadiusz Mastalerczuk

## Contact

- **E-mail:** [areqmas@gmail.com](mailto:areqmas@gmail.com)
- **LinkedIn:** [arkadiusz-mastalerczuk](https://www.linkedin.com/in/arkadiusz-mastalerczuk)
- **GitHub:** [arekmastalerczuk](https://github.com/arekmastalerczuk)
- **Codewars:** [arekmastalerczuk](https://www.codewars.com/users/arekmastalerczuk)

## Summary

I've always claimed that *I'm too weak to be **a developer***. It seemed to me that it was very difficult (and I still think so, as there is a lot of knowledge to learn) and I wouldn't be able to do it.

However, I decided that I wouldn't give up and show myself that I was wrong and that *I could become a developer!*

I started to learn frontend technologies (HTML, CSS, JS) about two years ago, with ups and downs.

**The milestone** was taking the backend course **[MegaK](https://www.megak.pl)**.

I really focused on learning a year ago, when during the course, in addition to gaining knowledge, I started writing my own code almost every day and learning backend technologies.

During that time I became more familiar with JavaScript, Node.js, Express and NestJS frameworks, learned what a REST API is and how databases work. I learned TypeScript, React, the basics of TDD (Jest) and how GIT works.

During this I wrote my first project [*Fly a Drone*](https://armast.networkmanager.pl) combining [backend](https://github.com/arekmastalerczuk/FlyADroneBack) (Express) and [frontend](https://github.com/arekmastalerczuk/FlyADroneFront) (React). Now I have a plan to refactor BE into **NestJS** and add some features on BE & FE like authorisation and authentication, file handling etc. I also participated in a group project *HeadHunter* where we used NestJS on [backend](https://github.com/Bartlomiej95/GR12-HeadHunter-backend) and React on [frontend](https://github.com/Bartlomiej95/GR12-HeadHunter-frontend) and I experienced the first GIT conflicts in teamwork.

I learned a lot, but there is still a much more to learn ahead of me, and one of the main problems was *the constant lack of time*, so I decided to quit my job and **focus on learning** JavaScript.

I also started studying at [RollingScopes School](https://github.com/rolling-scopes-school/js-fe-course-en) on the *JavaScript/Frontend* course to further expand my knowledge and grow as a developer. I also showed myself that *I was wrong*, and although it is not easy, but with hard work *I will be able to do what I really like and **become a Junior JavaScript developer!***

## Skills
- HTML5, CSS3
- JavaScript:
    - ES6+
    - OOP
    - FP
    - asynchronous
- Node.js
- TypeScript
- \[BE] frameworks:
    - Express
    - NestJS
- REST API
- Databases:
    - MySQL
    - MongoDB
- TypeORM
- React
- TDD basics \(Jest)
- GIT, Scrum, Agile

## Code examples

You can check my projects on GitHub: [arekmastalerczuk](https://github.com/arekmastalerczuk)

```javascript
  spotRouter
      .get('/search/:spotAddress?', async (req, res) => {
          const spots = await SpotRecord.getAll(req.params.spotAddress ?? '');
          res.json(spots);
      })
  
      .get('/:id', async (req, res) => {
          const spot = await SpotRecord.getOne(req.params.id);
          res.json(spot);
      })
  
      .post('/', upload.single('image'), async (req, res, next) => {
          const spot = new SpotRecord(req.body);
          await spot.insert();
          res.json(spot);
      });
```

## Experience

In my last job, I was responsible for implementing BIP pages in subordinate units, working with clients, conducting training courses and learned semantic HTML, accessibility principles and learned CSS.

In last year I attended the **MegaK** backend course and I wrote my first project [*Fly a Drone*](https://armast.networkmanager.pl) where I used Express framework on [backend](https://github.com/arekmastalerczuk/FlyADroneBack) and React library on [frontend](https://github.com/arekmastalerczuk/FlyADroneFront). I recently learned **NestJS** so I have a plan to refactor BE with that framework and add some features on BE & FE.

I also participated in a group project *HeadHunter* where we used NestJS on [backend](https://github.com/Bartlomiej95/GR12-HeadHunter-backend) and React on [frontend](https://github.com/Bartlomiej95/GR12-HeadHunter-frontend) and I experienced the first GIT conflicts in teamwork. I learned then the principles of SCRUM and Agile.

## Education

### School Education
- Katowice Institute of Information Technologies \(WSTI)
- Silesian Univercity of Technology in Katowice

### Courses
- [MegaK](https://www.megak.pl) - backend JavaScript course (Node.JS, Express, TypeScript, MySQL, MongoDB, NestJS, React)
- [WTF: Co Ten Frontend](https://cotenfrontend.pl) - frontend HTML, CSS & JavaScript course
- [RollingScopes School](https://github.com/rolling-scopes-school/js-fe-course-en) - JavaScript/Frontend course \(*in progress*) 
- Udemy courses \(FE & BE)

## Languages

- **English**: Intermediate \(B1)
- **Polish**: Native
