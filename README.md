# javascript-test-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JavaLesson3_1</title>
    <style>
        body {background-color: ;}
        h1 {color:coral;}
        main{float: right;
            width:85%;}
        aside{float:left;
            width:10%;
            margin-top: 15px;
           
            height:500px;
            position: absolute;
            
            
        }
        
        
        
        button{
            display: block;
            margin-bottom: 20px;
            margin-left: 10px;
            color: saddlebrown;
            background-color: #f2c197;
            text-decoration: none;
            text-align: center;
            font-size: 16px;
                
            }
        
    </style>
</head>
<body>
    <header>
    <h1>Spring Break Class Vacation Log</h1>
    <hr>
    </header>
    
    <main>
    <p> </p>
    <p id="fname"></p>
    <p id="lname"></p>
    <p id="bday"></p>
    <p id="des"></p>
    <p id="bprice"></p>
    </main>
    <aside>
    <button type= "button" onclick="
        studentVacation1()">Student 1</button>
    <button type= "button" onclick="
        studentVacation2()">Student 2</button>   
    <button type= "button" onclick="
        studentVacation3()">Student 3</button>  
    <button type= "button" onclick="
        studentVacation4()">Student 4</button>  
    </aside>
    <!-- batton for student 1. when the button is clicked the function studentVacation1 is run then all date is load in  the assigned paragraphs.-->
    
<script>
    /*var fname;
    var lanme;
    var bday;
    var des;
    var bprice;
    */
   
    function studentVacation1(){
        
        fname = "Smith";
        document.getElementById("fname").innerHTML = "First Name : " + fname;
        console.log(fname);
        
        lname = "Oh";
        document.getElementById("lname").innerHTML = "Last Name : " + lname;
        console.log(lname);
        
        
        
        bday = new Date(2000, 6, 26);
        document.getElementById("bday").innerHTML = "Birthday : " + bday;
        console.log(bday);
        
        des = "Seoul, South Korea";
        document.getElementById("des").innerHTML = "Destination : " + des;
        console.log(des);
        
        
        bprice = 1100;
        document.getElementById("bprice").innerHTML = "Booking Price : " + bprice;
        console.log(bprice);
    }
    
     function studentVacation2(){
        
        fname = "Jeffrey";
        document.getElementById("fname").innerHTML = "First Name : " + fname;
        console.log(fname);
        
        lname = "Wick";
        document.getElementById("lname").innerHTML = "Last Name : " + lname;
        console.log(lname);
        
        
        
        bday = new Date(1980, 3, 21);
        document.getElementById("bday").innerHTML = "Birthday : " + bday;
        console.log(bday);
        
        des = "NJ, America";
        document.getElementById("des").innerHTML = "Destination : " + des;
        console.log(des);
        
        
        bprice = 600;
        document.getElementById("bprice").innerHTML = "Booking Price : " + bprice;
        console.log(bprice);
    }
    
     function studentVacation3(){
        
        fname = "Bill";
        document.getElementById("fname").innerHTML = "First Name : " + fname;
        console.log(fname);
        
        lname = "Gaffield";
        document.getElementById("lname").innerHTML = "Last Name : " + lname;
        console.log(lname);
        
        
        
        bday = new Date(1999, 3, 16);
        document.getElementById("bday").innerHTML = "Birthday : " + bday;
        console.log(bday);
        
        des = "Osaka, Japan";
        document.getElementById("des").innerHTML = "Destination : " + des;
        console.log(des);
        
        
        bprice = 1500;
        document.getElementById("bprice").innerHTML = "Booking Price : " + bprice;
        console.log(bprice);
    }
     function studentVacation4(){
        
        fname = "Sally";
        document.getElementById("fname").innerHTML = "First Name : " + fname;
        console.log(fname);
        
        lname = "Ballard";
        document.getElementById("lname").innerHTML = "Last Name : " + lname;
        console.log(lname);
        
        
        
        bday = new Date(1979, 1, 21);
        document.getElementById("bday").innerHTML = "Birthday : " + bday;
        console.log(bday);
        
        des = "Beijing, China";
        document.getElementById("des").innerHTML = "Destination : " + des;
        console.log(des);
        
        
        bprice = 1800;
        document.getElementById("bprice").innerHTML = "Booking Price : " + bprice;
        console.log(bprice);
    }
    
    /*console.log (fname);
    console.log (lname);
    console.log (bday);
    console.log (des);
    console.log (bprice);
    */
    
</script>    
</body>
</html>

