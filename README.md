# countdown
<!doctype html>
<html>
    <head>
        <meta charset="uft-8">
        <title>countdown</title>
    </head>

    <body>
        <div class="output">
         
          
        </div>

        <script>

            const output = document.querySelector('.output');
           

            for(let i=10;i>=0;i--){
                const para = document.createElement('p');
                output.appendChild(para);  
                if(i===10){
                  para.textContent = 'Countdown ' + i;
                }else if(i===0){
                  para.textContent = 'Blast off!';
                }else{
                  para.textContent = i;
                } 
              
            }



        </script>

    </body>
</html>
