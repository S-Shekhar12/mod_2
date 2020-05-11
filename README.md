
<!DOCTYPE html>
<html>
<head>
    <title>Second Assignment</title>
    <meta charset="utf-8">
    <meta name-"viewport" content="width-device-width, initial-scale-1">
    <style>
    	div{
    		border:1px solid black;
    		margin: 20px;
    		background-color:orange;
    		width:30%;
    		color:white;
    	   }
    	h1{
    		text-align: center;
    	  }
    	h4{
    		text-align: center;
    	  }
    	.p1{
    		text-align: top-right;
    		height:35px;
    		width:100px;
    		background-color:yellow;
    		color:red;
    	   }
    	@media(min-width:1200px){
    	div{
    		float:left;
    	    }
        }
    	@media(min-width:992px) and (max-width:1199px){
    		div{float:left;
    		}
    		.d1{
    		    width:80%;
    		}
    		.d2{
    		    width:40%;
    		}
    	}
    	@media(max-width:991px){
    		div{
    			float:bottom;
    		}
    		.d3{
    		    width:90%;
    		}
    	}
    </style>
</head>
<body>
	<h1>Our Menu</h1>
	<div class="d2 d3"><p class="p1">Sweet</p>The definition of sweet is a description for a person who is nice or for something that tastes good and that is usually sugary. An example of sweet is the way you describe a generally nice girl that everyone likes. An example of sweet is the way you would describe the taste of cake or candy.</div>
	<div class="d2 d3"><p class="p1">Pizza</p>Pizza is a savory dish of Italian origin, consisting of a usually round, flattened base of leavened wheat-based dough topped with tomatoes, cheese, and often various other ingredients (anchovies, olives, meat, etc.) baked at a high temperature, traditionally in a wood-fired oven.[1] A small pizza is sometimes called a pizzetta.</div>
	<div class="d1 d3"><p class="p1">Ice-cream</p>Ice cream is a mixture of milk, cream, sugar, and sometimes other ingredients, that has been frozen into a soft, creamy delight using special techniques. Ice cream has been a popular treat for hundreds of years but only become commonplace since the widespread use of refrigeration.</div>
</body>
</html>
