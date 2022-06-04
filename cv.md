## **Alena Petrash**
Junior Front-End Developper

[Linkedin](https://www.linkedin.com/in/alena-petrash-76b6051a1/)\
[Github](https://github.com/egordylan)\
[Email](helen.y.petrash@gmail.com)

### About me:
I love working with smart, ambitious, and kind people.
I am an excellent team worker, responsible, have good analytical and problem-solving skills. I`m self-motivated and hard-working person.
I can work in a team and in stressful situations. I received only positive reviews about working with me. I study English in my free time and learn technologies which are new for me. My hobby is reading books, drumming, traveling.

======================================================================================================================================================

### Hard skills:
* JavaScript
* Python 3
* Base knowleges of MySQL
* HTML/CSS
* Git
* BDD/TDD
* WebdriverIO
* Cucumber
* Mocha + chai

======================================================================================================================================================

### Code example:
_Find the last number between 1 and n (inclusive) that survives the elimination process. Start with the first number on the left then remove every other number moving right until you reach the the end, then from the numbers remaining start with the first number on the right and remove every other number moving left, repeat the process alternating between left and right until only one number remains which you return as the "last man standing"._

[Codewars](https://www.codewars.com/kata/567c26df18e9b1083a000049)

```
function lastManStanding(n){
    let array = Array.from({length: n}, (val, num) => num + 1);
    let result = [...array];
    let len = array.length;
    while (len !== 1){
        result = result.filter((elem, index) => index % 2);
        len = result.length;
        result.reverse();
    }
    console.log(result);
    return result[0];
}
```

======================================================================================================================================================

### Experience:
**06/2014 – 08/2021 Republican scientiﬁc-design company "Institute of regional and urban planning"** _Minsk, Belarus_

Urban planning specialist/ 1st category architect
* Collection of the initial data for the development of urban planning projects
* Urban planning design (general and detailed plans)
* Technical support of urban planning projects
    
**02/2014 - 06/2014 Catalogue of Saint Elisabeth Convent** _Minsk, Belarus_

Artist of painting on wood of the 4rth category
* Painting on wood and ceramics
            
**08/2013 – 12/2013 Center For The Regeneration Of Historical And Cultural Landscapes And Territories** _Minsk, Belarus_

Architect
* Collecting data of measurements of exteriors and interiors of buildings
* Registration of architectural drawings according to measurements
     
**08/2010 - 08/2012 Branch of Belarusian National Technical University "Minsk state architectural-construction college"** _Minsk, Belarus_

Teacher of special disciplines

======================================================================================================================================================

### Education:
* 2022 - now: _Javascript/Front-End. Stage 0(in progress)_ **Rolling Scopes School**
* 02/2022 - 04/2022: _JavaScript Automation QA training for Beginners_ **Exadel**
* 2021: _Generation Python: course for beginners_ **www.stepik.org**
* 2021: _Python Complete Course For Python Begginers_ **www.udemy.com**
* 09/2010 - 12/2011: _Master of architecture/ MArch - Urban design_ **Belarusian National Technical University**
* 09/2005 - 06/2010: _Bachelor of architecture/ BArch - Urban design, architecture_ **Belarusian National Technical University**

======================================================================================================================================================

### Languages:
* English - A2
* Belarussian - native
* Russian - native