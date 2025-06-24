# Test-2

    console.log("my name is Darlington Levi\n  we are having a react n Bootcamp");
    console.log("I am a software developer")
    console.warn("Standby! This is the last warning");
    console.error("you cannot divide a number by zero")
    document.writeln("I am learning javascript<br>")
    document.write("I want to be a frontend developer")
    alert("welcome to my website")
    prompt("Enter your name");
    let name = prompt("Enter your name")
    console.log("The entered name is ", name );

    // simple calculator
    //let num1 = prompt("Enter the first number");
    //num1  = parseInt(num1)

    //let num2 = prompt("Enter the second number");
    //num2  = parseInt(num2)

    //console.log(""+num1+" + "+num2+" =", num1+num2)
    //console.log(`${num1}-${num2}=${num1-num2}`)

    console.log("The ramdom generated number is",Math.random())
    console.log("The square root of 12 is",Math.sqrt(25))
    console.log("The maximum number in the set is ",Math.max(12,17,80,65,4))

    // let, var, const
    //let firstname //declare a variable called name
    //var age = 14 // declared and initialized variable age
    //const pi = 3.14

    //firstname = prompt("Enter your first name")
    //console.log(`my first name is ${firstname}`)

   // var age = prompt("how old are you")
   // age = parseInt(age)
    //console.log(`Iam ${age}years old`)

    //const pi = 3.14
    //console.log("The value of pi is"+pi)

    //let wild_animal ="lion"
    //var domestic_animal ="cow"
    //console.log("wild_animal,domestic_animal")

    // escape sequences
    console.log("\"my name is Darlington Levi\"  we are having a react n Bootcamp\'");

    let number = 24
    let d = 4.45
    let e = 5e10

    let isMale = true
    var haspaid  =true

    
    let str1 = "iam good at javascript"
    //let str2 = "iam good at ja"
   // console.log("The 2 statements are same:",str1===str2)

   // let sym1 =  symbol("iam good at ja")
    //let sym2 = symbol("iam good at ja")
    //console.log("The 2 statements are same:",sym1===sym2)

   //var weight;
   // console.log("The value of weight",weight);

    var height = null
    console.log("The values of height",height)

    // typeof to get the dataype
    let x = 56
    let y = "Levi"
    let z = true
    let m = undefined
    let n = null
    console.log("The data type of  x is "+ typeof x)
    console.log("The data type of  y is "+ typeof y)
    console.log("The data type of  z is "+ typeof z)
    console.log("The data type of  m is "+ typeof m)
    console.log("The data type of  n is "+ typeof n)

    // converting the from one datatype to another
    let num = 6
    console.log("The datatype of a num before changing it is"+typeof num)
    num = String(num)
    console.log("The datatype of a num after changing it is"+typeof num)

    let  p  = "18"
    console.log("The datatype of p before changing it is"+typeof num)
    p = Number(p)
    console.log("The datatype of p after changing it is"+typeof num)

    let k = "true"
    console.log("The datatype of k before changing it is"+typeof k)
    if(k==="true"){
        console.log("k is a String")
    }else{
        console.log("k is a boolean")
    }
    k=Boolean(k)
    console.log("The datatype of k after changing it is"+typeof k)

    //Operators
   /* Arithimetic(+,-,/,*,%,**)
    Unaray(**,--)
    logical (&&, ||,!)
    comparison(==,===,!==,>,<)
    */
   let a = 2
   let b =4
   console.log(`${a}+${b}=${a+b}`)
   console.log(`${a}-${b}=${a-b}`)
   console.log(`${a}*${b}=${a*b}`)
   console.log(`${a}/${b}=${a/b}`)
   console.log(`${a}%${b}=${a%b}`)
   console.log(`${a}**${b}=${a**b}`)

   console.log('a++',a++)// 4 first prints the value before adding it
   console.log('++a',++a)// 6 it adds the value before using it

   console.log('b--',b--)// 1 first print the value before subtracting
   console.log('--b,--b')// 1

   //logical//
   let h =8
   var f= 5
   let j= 10
   let u = true
   console.log("h>f&& f<j",(h>f && f<j))// true
   console.log("h>f || f<j",(h>f && f<j))// true
    console.log("!u",!u)

    let r = 5
    let q = "5"

    console.log("r==q",r==q) // checks the values if they are the same return true
    console.log("r ===q",r===q) //srictly equal,checks if values are the same and also if the data type is the same

    console.log("h > f", h>f)//true
    console.log("f<j",f>j)//false
    