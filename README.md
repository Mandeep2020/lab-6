# lab-6// JavaScript Document



// 1.) Create an object to represent you.
let myinfo = {



    // 2.) In your object, add the following members 

         //a.)first name
         //b.)last name
         //c.) program 
         //d.) where you call home 
         //e.) interests 
         //f.) a function that creates an alert that displays 'Hi, I am' and your name
         //g.) a function that creates an alert that displays all your information;
      myname: {
      myfirstname: 'Mandeep',
      mylastname: 'Kaur' 
      },

      myprogram: 'Computer Programmer',
      myhome: 'Mississauga',
      myinterests: ['singing', 'dancing', 'reading'],
      msg: function () {
        alert('Hi, I am' + myinfo.myname.myfirstname + myinfo.myname.mylastname)
    }, 
    totalinfo: function() {
    alert('My name is ' + myinfo.myname.myfirstname + ' ' + myinfo.myname.mylastname + 'and I am enrolled in ' + myinfo.myprogram + ' I am living in ' + myinfo.myhome +
                  'and I like to do ' + myinfo.myinterests[0] + ' ' + myinfo.myinterests[1] + ' ' + myinfo.myinterests[2] + '.')
      }
    
}

//3.) add a new object member that display your biggest pet peeve (something that bothers or annoys you)
myinfo.thingbotherme = 'loud chewing';

//4.) delete your last name 
delete myinfo.myname.mylastname;

//5.) Using dot or bracket notation, demonstrate how to access your first name. 
myinfo.myname.myfirstname;

//6.) Using dot or bracket notation, demonstrate how to access the function that displays all your information. 
myinfo.totalinfo();





