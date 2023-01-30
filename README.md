# Javascript-ES6

```
ECMAScript 2015 was the second major revision to JavaScript.

ECMAScript 2015 is also known as ES6 and ECMAScript 6.

This chapter describes the most important features of ES6.
```
# Literal Object Improvement.
```javascript
const name = "Timo Web";
        const age = 30;
        const specialty = 'Developer'
        const academics = 'ADSE'

        var student = {
            /*************es5***************/
            name: name,
            age: age,
            academicDetails: function () {
                console.log(`My name is ${this.name} and i have an a ${this.academics} diploma`)
            },
            /*************es6***************/
            specialty,
            academics,
            workDetails() {
                console.log(`My name is ${this.name} and i am a ${this.specialty}`)
            }
        }
        student.academicDetails();
        student.workDetails()
```
