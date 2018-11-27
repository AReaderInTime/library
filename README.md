# library
Library Website (INCOMPLETE) 
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Game (for final) </title>
        <style>
            #book-pic {
                border: 1px solid blue;
                width: 350px;
            }
            
            #book-text { 
                font-family: Monospace;
                color:rgb(17, 34, 222);
            } 
            body {
                background-color: rgb(179,179,179);
            }
        </style>
    </head>
    <body>
    
        <img id="book-pic" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Urval_av_de_bocker_som_har_vunnit_Nordiska_radets_litteraturpris_under_de_50_ar_som_priset_funnits_%283%29.jpg/220px-Urval_av_de_bocker_som_har_vunnit_Nordiska_radets_litteraturpris_under_de_50_ar_som_priset_funnits_%283%29.jpg">
        
        <h1 id="book-text"> Library Galore! </h1>
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
        
     <ul> 
         
         <li> <a href= "#book-viewing"> View your books </a>  </li> 
         <li> <a href = "#read-year"> View the books you have read this year </a> </li> 
         <li> <a href = "#books-own"> See how many books you own!</a> </li> 
     </ul>
     
     <h2 id = "book-viewing"> Your Books</h2>
     <ol> 
         <li> The Hate U Give by Angie Thomas </li> 
         <li> Six of Crows by Leigh Bardogo </li>
         
     </ol>
     
        
        <script>
      
        $("#book-pic").animate ({
              width: "400px",
            marginLeft: "30px",
            borderWidth: "10px"
        }, 1500);
        
        $("#book-text").animate({
           marginLeft: "50px",
           fontSize: "3em"
        });
          
        </script>
        
    </body>
</html>
