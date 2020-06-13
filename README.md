<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practica 2</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap" rel="stylesheet">
</head>
<body>
     
    <!--AQUI PONDRE LA IMAGEN Y LOS NAV-->
    
  <div>
    
 
   <nav>
    <img src="CODE.png" id="Logo">
    <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Creepypastas</a></li>
        <li><a href="#">Redes sociales</a></li>
    </ul>
</nav>
</div>


<!--LA IMAGEN CENTRAL-->
<header>
 <article id="Creepys">
<h1>
    Leer Creepypastas
</h1>
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus mollitia perferendis earum?
</p>
<p id="Border"><a href="#">Más Informacion</a></p>
</header>
</article>
 <!--AQUI ESTAN LOS ARTICULOS--> 
<article>
    <div>
    <h1>
            Slenderman
    </h1>
    <p>
        <img class="Imagen" src="Slenderman.jpg"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum iste iure blanditiis. Asperiores fuga et, dolores vel ea aliquam doloribus natus odit tempore optio voluptatum, quasi cumque vitae vero delectus quidem facere. Tempora facere debitis necessitatibus et, quaerat nemo excepturi labore qui nihil, accusantium dignissimos laudantium consequatur. Autem magnam, rerum veritatis consequuntur nesciunt officiis nisi est a laborum dolorem! Temporibus, quis reiciendis. Illo consectetur saepe reprehenderit cumque porro harum? Non nihil esse necessitatibus ipsum quia dolores voluptatum temporibus quas eveniet obcaecati natus ducimus recusandae et sed a similique, eligendi, ullam iure unde laboriosam doloremque veniam? Sequi, labore debitis dolorem vero sint, non placeat recusandae, ullam cum neque libero consequuntur perspiciatis quasi dignissimos eius itaque maxime at. Rerum molestiae numquam aspernatur, fugit corrupti vitae dicta?
    </p>
    <p class="Border">
        <a href="#">Leer más</a>
    </p>
    
</div>
</article>

<article>
    <div>   
    <h1>
            Sonic.exe 
        </h1>
        <p>
           <img src="Sonic exe.png" class="Imagen">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Amet iusto ad, sapiente quaerat ut neque dolore voluptatem sequi, tenetur nihil soluta delectus temporibus quas? Et cum consectetur suscipit reprehenderit accusamus praesentium sunt ipsa nam sint iure ullam totam possimus, aliquam aliquid repudiandae vitae voluptates eius? Amet alias, temporibus fugit reiciendis quisquam autem eaque, eligendi, sequi odio praesentium laboriosam optio sunt numquam cumque! Cumque, excepturi quidem. Officia, cumque sequi fuga soluta amet veritatis enim natus iste exercitationem quaerat tempore alias, ducimus iure provident ipsum suscipit reprehenderit molestias illum dolore minus impedit, odio minima! Quis suscipit reprehenderit ratione laudantium qui accusamus amet dolores. Laboriosam molestiae vero esse, nulla assumenda architecto consectetur temporibus facilis delectus nemo ipsa cumque fugit optio nihil quibusdam odio expedita blanditiis rerum beatae necessitatibus. Earum voluptates sapiente deserunt cupiditate non nam!
        </p> 
        <p class="Border">
            <a href="#">Leer más</a>
        </p>
    </div>
</article>

<article>
    <div>   
    <h1> 
           Ben Drowned 
        </h1>
    
        <p> <img src="Ben.jpg" class="Imagen">
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores debitis soluta quo quasi, harum natus. Non assumenda nemo praesentium, voluptates eaque nisi incidunt quo aliquid quaerat! Dicta blanditiis sit libero nobis, neque aut, quam dolorum natus unde, adipisci similique eius magnam reiciendis soluta voluptatem aspernatur ex omnis cum recusandae suscipit officiis. Distinctio molestias voluptatem quam doloribus facere harum rerum quo repellat illo fugit aspernatur expedita dolore, labore vel error maxime officiis recusandae aliquam exercitationem cumque, et qui sit. Sit magnam deserunt ut consequatur, ipsum doloremque itaque voluptatum fuga cupiditate, dolore, natus maiores maxime? Quo nostrum assumenda nam at, earum sit! Quo praesentium quaerat, animi corrupti error harum excepturi voluptatum accusantium quae modi possimus natus veritatis unde saepe fuga facere nesciunt deserunt maxime! Incidunt?
        </p>
        <p class="Border">
            <a href="#">Leer más</a>
        </p>
    </div> 
</article>

<!--AQUI VA LA PIERNA DE LA PAGINA-->
<footer>
    <p>
        <strong>
            Samil Moret - 12/06/2020
        </strong>
    </p>
</footer>

</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    position: relative;
    margin: 5%;
    background: black;
    color: white;
    margin-top: 0;
}

ul {
    list-style: none ;
}

nav {
    display: flex;
    font-size: 30px;
    padding: 1cm;
    font-family: 'Oswald', sans-serif;
    margin-top: 20px;

}

li {
    display: inline;
    margin: 20px;
    margin-left: 2cm;
}

#Logo {
    width: 1.5cm;
    border: solid white 1px;
}

a:hover {
    border-bottom: red 2px solid ;
}

a {
    text-decoration: none;
    color: red;
    font-family: 'Oswald', sans-serif;
}

#Creepys {
    width: 10cm;
    margin-left: 6cm;
    background: url(./Creepypastas\ comiendo.jpg) no-repeat center/cover;
    width: 13cm;
    height: 17cm;
    padding-bottom: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content:flex-end;
    text-align: center;
}


p {
    padding: 10px;
    margin-left:  20px;
}

article {
    padding: 20px;
    background: rgb(47, 46, 46);
    margin-top: 30px;
    position: relative;
}

h1 {
    padding: 10px;
}

.Border {
    border: 2px white solid;
    width: 80px;
    background: rgb(47, 46, 46);
    margin-top: 30px;
}

#Border  {
       border: 2px white solid;
       background: rgb(47, 46, 46) ; 
       margin-top: 10px;
}

footer {
    text-align: center;
    padding: 50px;
    background: rgb(31, 28, 31);
    margin-top: 30px;
    position: relative;
}

.Imagen {
         float: right;   
         width: 4cm;
         padding-left: 20px ;
}
