# homework-6
homework 6
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        // question 1
        const ucFirst = (str) =>{
          return str[0].toUpperCase()+str.slice(1)
        }
        ucFirst('blah')
        //question 4
        var name= "$";
        console.log("$","")

       
        // question 2
        var name5 = "sex";
        
        console.log(name5.replace("sex", "sus"));
        var name2 = "free";
        console.log(name2.replace("free", "sus"));
        var name3 = "viagra";
        console.log(name3.replace("viagra", "sus"));
        var name4 = "porn";
        console.log(name4.replace("porn", "sus"));
       //question 3
        var truncate = function (elem, limit, after) {

        if (!elem || !limit) return;
          var content = elem.textContent.trim();


          content = content.split(' ').slice(0, limit);


          content = content.join(' ') + (after ? after : '');


          elem.textContent = content;

          };

      var elem = document.querySelector('.truncate');
      truncate(elem, 7, '...');
      
      //question 6
      e=2
      let str2 = ["jazz","blues"];
      str2.push("rocknroll");
      str3=none;
      str2.length=str3;
      int(str3);
      str4=none;
      str4=str3 / e
      str2[str4].replace("classics")
      str2[0].replace("")

      function removeSpaces(str) {
          var count = 0
          for (var i = 0; i < str.length; i++)
            if (str[i] !== " ") str[count++] = str[i];
          return count;
       //q7
      }
      var str="y e e t"
      var i=removeSpaces(str);
      document.write(str.join("")).substring(0,i));
    //question 8
      function filter(arr,a, b) {
        return arr.filter(item=>(a<= item && item <=b));
      }

    </script>
    <div class="truncate">
        1234567891011121314151617181920212223242526272829303132333435363738394041424344454647484950
    </div>
</body>
</html>
