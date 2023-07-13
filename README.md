# PIAIC-Assignment1

//Question-2
let a = "Hello Uzair, How are you?";
console.log(a);

//Question-3
let b = "uZaIr";
let c = b.toUpperCase(); 
console.log(c);

let d = b.toLowerCase();
console.log(d);

// let e = b.toTitleCase();
// console.log(e);

//Question-4
console.log('Sir Francis Bacon said,"Knowledge is Power"');

//Question-5

let famous_person = 'Sir Francis Bacon said,"Knowledge is Power"';
console.log(famous_person);

//Question-6

let f = "U \tz \ta \ti \tr \n\tR \ta \tz \ta";
console.log(f);

//Question-7

console.log(4+4);
console.log(10-2);
console.log(4*2);
console.log(16/2);


//Question-9

let favorite_number = 7;
console.log("Favorite Number"+ " "+ "="+ favorite_number);

//Question-10

// let g = "I am Pakistani";
// console.log(g);

let h = "Pakistan is very beautiful";
console.log(h);

//Question-11

let friends_name = ["Amman", "Usama", "Ajaz"];
console.log(friends_name[0]);
console.log(friends_name[1]);
console.log(friends_name[2]);

// Question-12

let greeting = "How are you?"
console.log(friends_name[0]+ ", "+greeting);
console.log(friends_name[1]+ ", "+greeting);
console.log(friends_name[2]+ ", "+greeting);

//Question-13

let mode_of_transport = ["Car", "Bikes", "Bus"];
console.log("I like Carrolla Gli"+ " " +mode_of_transport[0]);
console.log("Yamaha is great brand in"+ " " +mode_of_transport[1]);
console.log(mode_of_transport[2]+" "+"is a good way to tour round the city.");

// Question-14

let guest_list = ["Shoaib", "Zohaib", "Saqib"];
let invitation_message = ", You are cordinally invited to dinner party at my place, \n we will feel pleasure to have your company";

console.log(guest_list[0]+invitation_message);
console.log(guest_list[1]+invitation_message);
console.log(guest_list[2]+invitation_message);

//Question-15

guest_list.pop();
guest_list.push("Kashif");
console.log(guest_list[0]+invitation_message);
console.log(guest_list[1]+invitation_message);
console.log(guest_list[2]+invitation_message);

//Question-16

// Adding three more people
guest_list.push("Saad");
guest_list.push("Kumail");
guest_list.push("Yasir");

// Changes in Invitation msg
invitation_message = ", You are cordinally invited to dinner party at my place, \n we will feel pleasure to have your company. \nWe want to have big dinner party with you all so we invited more people.";

//print revised message to guest
console.log(guest_list[0]+invitation_message);
console.log(guest_list[1]+invitation_message);
console.log(guest_list[2]+invitation_message);
console.log(guest_list[3]+invitation_message);
console.log(guest_list[4]+invitation_message);
console.log(guest_list[5]+invitation_message);


// Adding One New guest in Beginning of Array

guest_list.unshift("Huzaifa");
console.log(guest_list[0]+invitation_message);

// Adding One New guest in Middle of Array

guest_list.splice(3, 0, "Basit");
console.log(guest_list[3]+invitation_message);

// Adding one more guest at end of list and re-print
guest_list.push("Sheraz");
console.log(guest_list);

console.log(guest_list[0]+invitation_message);
console.log(guest_list[1]+invitation_message);
console.log(guest_list[2]+invitation_message);
console.log(guest_list[3]+invitation_message);
console.log(guest_list[4]+invitation_message);
console.log(guest_list[5]+invitation_message);
console.log(guest_list[6]+invitation_message);
console.log(guest_list[7]+invitation_message);
console.log(guest_list[8]+invitation_message);

// Question-17
// Shrinking Guest list

invitation_message = " I regret to inform that due to unavailability of Dinner Table in Resturant. I am cancelling the the dinner, I will soon plan for dinner party some other time."

console.log(guest_list[2]+invitation_message);
console.log(guest_list[3]+invitation_message);
console.log(guest_list[4]+invitation_message);
console.log(guest_list[5]+invitation_message);
console.log(guest_list[6]+invitation_message);
console.log(guest_list[7]+invitation_message);
console.log(guest_list[8]+invitation_message);

// Remove guest from list

guest_list.pop();
guest_list.pop();
guest_list.pop();
guest_list.pop();
guest_list.pop();
guest_list.pop();
guest_list.pop();

// Letting know remain two guests for dinner

invitation_message = ", I just want to remind that you are invited to dinner party and due to unavailbility of big dinner table, I am inviting few people this time."

console.log(guest_list[0]+invitation_message);
console.log(guest_list[1]+invitation_message);


//Question- 18

let country = ["Canada", "Australia", "Italy", "UK"];
console.log(country);

// Array in alphabetical order
country.sort();
console.log(country);

// Array in reverse alphabetical order
country.reverse();
console.log(country);

// Reverse again to bring in previous order

country.reverse();
console.log(country);
 
//Question- 19
//Number of Guest invited to Dinner
console.log("Number of guests invited"+ " = "+guest_list.length);
console.log(guest_list);

// Question- 20
let cities = ["Karachi", "Lahore", "Islamabad", "Rawalpindi"];
console.log("Four Famous cities of Pakistan");
console.log(cities[0]);
console.log(cities[1]);
console.log(cities[2]);
console.log(cities[3]);

// Question- 21

let Pakistan = {capital:"Islamabad",language:"Urdu", animal:"Markhor"};
console.log(Pakistan);

// Question- 22

let fruits = ["orange","mangos","apple"];

// console.log(fruits{0});

// Question- 23
//Example-1
let car1 = "Civic";
if (car1=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-2
let car2 = "Mehran";
if (car2=="Mehran"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-3
let car3 = "City";
if (car3=="City"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-4
let car4 = "Audi";
if (car4=="Audi"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-5
let car5 = "Wagon R";
if (car5=="Wagon R"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-6
let car6 = "Yaris";
if (car6=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-7
let car7 = "Santro";
if (car7=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-8
let car8 = "Jeep";
if (car8=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-9
let car9 = "Corrolla";
if (car9=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}

//Example-10
let car10 = "Mira";
if (car10=="Civic"){
    console.log("True");
}
else{
    console.log("False");
}


// Question- 24

//Test equality and in equality with string
let Pakistan_Capital = "Islamabad";

if (Pakistan_Capital=="Islamabad"){
    console.log("True");
}
else{
    console.log("False");
}

// Test using lower Case

let Famous_scientist = "albert Estine";
if (Famous_scientist == "Albert Estine"){
    console.log("Correct");
}
else{
    console.log("Wrong");
}

// Test AND and OR

let value1 = 6;

if(value1 > 4 && value1 <10){
    console.log("True");
}
else{
    console.log("False");
}

let value2 = 4;
if(value2 > 6 || value2 < 10 ){
    console.log("True");
}
else{
    console.log("False");
}


// If condition  when object in Array

const fruits1 = ["Apple", "Orange", "Apple", "Mango"];
if (fruits1.indexOf("Apple") + 1){
    console.log("Found");
}
else{
    console.log("Not Found");
}


// If condition when object is not in Array
const fruits2 = ["Banana", "Orange", "Grapes", "Mango"];
if (fruits2.indexOf("Apple") + 1){
    console.log("Found");
}
else{
    console.log("Not Found");
}




























