﻿# js-module-2-assignment
# module3_es6Assignment



// 01 javascript for in loop

/*  let person = {
    name:"Asif Khan",
    age:22,
    email:"asif@gmail.com",
    print:function(){
        console.log(person.name,person.email);
    }
        
}
PrintObjP(person)
function PrintObjP(person){
    for(let value in person){
        if(person[value] == "" ){
            console.log("object is empty");
        } else{
            console.log(value+ " = "+person[value]);
        }
    }
}

*/

// 02 Javascript return function

 /* function findMaxNumber(num){
        if(num.length ===0){
            return null;
        } else{
           return  Math.max(...num)
        }
}


console.log(findMaxNumber([10,20,5,30,25]));

const numbers = [5,15,7];
console.log(findMaxNumber(numbers));

const emtyArray = [];
console.log(findMaxNumber(emtyArray));

*/

// 03 javascript spread Operator



/* function mergeArray(arr1,arr2){

    return [...arr1,...arr2]

}


const arr1 = [1,2,3];
const arr2 = [4,5,6];

console.log(mergeArray(arr1,arr2));

*/

// 04 javascript arrow function

/* let calcolateSquare = (number)=>{
        return number * number;
}

console.log(calcolateSquare(5));
console.log(calcolateSquare(8));

*/

//05 javascript es6 map

/* function doubleNumber(arr){
    return arr.map(array=> array * 2)
}

const numbers = [1,2,3,4,5];
console.log(doubleNumber(numbers));

*/


//06 Javascript es6 static keyword

/* class MathUtility{
    static multiply(a,b){
        return a*b;
    }
}

console.log(MathUtility.multiply(5,3));
console.log(MathUtility.multiply(2,8));

*/

//07 javascript es6 class inheritance 

/* class Animal {
    constructor(name,sound){
        this.name = name;
        this.sound = sound;
    }
    makeSound(){
        console.log(this.sound);
    }
}

const animal =  new Animal("Lion","Roar");
animal.makeSound()


const dog =  new Animal("Lion","Roar");

*/

//08 javascript es6 super keyword 

/*  class Person{
    constructor(name,age) {
        this.name = name;
        this.age = age;
    } 
    introduce(){
        console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
    }

    
}

class Student extends Person{
    introduce(){
        console.log(console.log(`Hello, my name is ${this.name} and I am ${this.age} years old. I am majoring in computer Science.`));
    }
}

const person1 = new Person("John",30);
person1.introduce();

const student1 =  new Student("Alice", 20);
student1.introduce()

*/
