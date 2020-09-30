# websiteusingbreadcrumbs
<html>
    <head>
       <meta name="viewport" content= 
		"width=device-width, initial-scale=1"> 

	<link rel="stylesheet" href= "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"> 

	<script src= "https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"> </script> 

    <script src= "https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"> </script> 
   <!--<link href= 
        "https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.css"
                rel="stylesheet" /> 
          
            <script src= 
        "https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.js"> 
            </script>-->
            <style>
                 .breadcrumb-item + .breadcrumb-item::before {
        content: "<<";
        color: black;
    }
            </style>

    </head>
    <body>
        <div class="bs-example" >
            <nav >
                <ol class="breadcrumb" class="nav nav-pills" style="background-color: rgb(6, 151, 248);height: 70px;font-size: 25px;padding-bottom: 25px;;">
                    <label style="font-size: 50px;">asos</label>
                    
                    <li class="breadcrumb-item"><a data-toggle="collapse" href="#home">Home</a></li>
                    <li class="breadcrumb-item"><a data-toggle="collapse" href="#products">Products</a></li>
                    <li class="breadcrumb-item"><a data-toggle="collapse" href="#cloth">Clothing</a></li>
                    <li class="breadcrumb-item"><a data-toggle="collapse" href="#brand">Brands</a></li>
                    <li class="breadcrumb-item active">Accessories</li>
                </ol>
            </nav>
        </div>
       
        <div id="home" class="collapse" >
           <p style="font-size: x-large;background-color:  red;"> Asos’s use of a muted color palette and minimalist design draws our attention on the clean photographs of their clothing as well as their subtle but unique use of animation throughout the site.</p>
        </div>
        <div id="products" class="collapse">
            <p style="font-size: x-large;background-color:  violet;">Respecting people, animals and planet with great products that our customers can trust.”  

            Our sourcing strategy focuses on three key areas: ethical trading, sustainable sourcing and animal welfare.This year we’ve collaborated closely with suppliers, brands, governmental and non-governmental organisations to address specific social and environmental challenges, in order to support and move towards long-lasting, industry-wide change.

        </p></div>
        <div id="cloth" class="collapse " ><p style="font-size: x-large;background-color: purple;">We believe in a world where you have total freedom to be you, without judgement. To experiment. To express yourself. To be brave and grab life as the extraordinary adventure it is. So we make sure everyone has an equal chance to discover all the amazing things they’re capable of – no matter who they are, where they’re from or what looks they like to boss. We exist to give you the confidence to be whoever you want to be.

            </div>
        <div id="brand" class="collapse " ><p style="font-size: x-large;background-color: orange;">We’re all about helping young talent – from cool new models to inspiring new voices, and it extends to more than just the world of fashion. We nurture creative peeps from all industries, so they can achieve brilliant things. Photographers, chefs, musicians… you name it, we find amazing people from around the world and help them to pursue their passion projects.

        </p></div>
        <div style="font-size: x-large;background-color: pink;">Whether you’re all about less is more or you’re an all-in kind of dresser, our men’s accessories are lined up to put the finishing touch on your outfits. Wedding and work looks are on lockdown with our selection of ties. Find subtle textures, florals, checks and the whole spectrum of colours to match your style and step your suit game up a level. ASOS DESIGN lets you find stand-out festival pieces, sunglasses, men’s hats, and a serious selection of jewellery for those details that complete the look. Get hands-free style courtesy of the collection</div>
       
    </body>
</html>
