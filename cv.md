# Tetiana Los
### Release Train Engineer
***
### Contact Information
* Location: Chernihiv, Ukraine
* Phone number: +38 (066) 57-46-453
* E-mail: tanya.v.los@gmail.com
* [LinkedIn profile](https://www.linkedin.com/in/tatiana-los)
* Discord: Tetianalos#9892
***
### About Myself
Currently, I work as a Release Train Engineer and closely communicate with Scrum Masters. Agile methodology is my passion and I'm constantly improving as a Scrum Master, coach, and facilitator. Meanwhile, due to the variety of duties, I usually communicate with Product Managers and development teams. That is my second direction of development. In order to get more technical background, I've started learning JavaScript.

Besides that, I'm an open-minded, responsible person with an active life position. I have good communication skills and the ability to reach positive results in discussions with co-workers and stakeholders. When I have free time, I enjoy traveling, riding a bicycle, running, reading, and spending lovely time with my relatives and friends.

My closes goal is to get the basics of JavaScript, get acquainted with motivated people in this course, and move forward towards new opportunities and challenges.
***
### Skills and Proficiency:
* Atlassian products: Confluence and Jira
* Balsamiq, LucidChart, Trello, Basecamp, MS Office, Adobe Photoshop
* Basic QA experience in Mantis Bug Tracker, TestLink
* Basic HTML, PHP, SQL
***
### Example of code
*Our football team has finished the championship. Our team's match results are recorded in a collection of strings. Each match is represented by a string in the format "x:y", where x is our team's score and y is our opponent's score.*
*Points are awarded for each match as follows:*
* *if x > y: 3 points (win)*
* *if x < y: 0 points (loss)*
* *if x = y: 1 point (tie)*
*We need to write a function that takes this collection and returns the number of points our team (x) got in the championship by the rules given above.*
*Notes: our team always plays 10 matches in the championship.*
* *0 <= x <= 4*
* *0 <= y <= 4*
```
function points(games) {
  let total = 0;
  games.map(game => {
    if (game[0] === game[2]) {
      total += 1;
    } else if (game[0] > game[2]) {
      total += 3;
    }
  });
  return total;
}
```
***
### Education
* Chernihiv Technological University (finance Department)
* Certified SAFe 5 Scrum Master
* Certified SAFe 5 Agilist
* “Become a Product Manager” course by Cole Mercer and Evan Kimbrell
* “Basics of software testing” course by QATestLab (group 68)
***
### Languages
* Ukrainian - native
* English - C1
* French - basic
