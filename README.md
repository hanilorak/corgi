<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>project</title>
    <style>
        body {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background:radial-gradient(1091px at 106.5% 111.5%, rgb(250, 246, 213) 0.1%, rgb(218, 147, 93) 42.2%, rgb(137, 86, 67) 74.3%, rgb(122, 104, 104) 100.2%);
        }
      h2,
      p {
        text-align: center;
        max-width: 800px;
        margin: 0 auto;
        padding: 10px 0;
        line-height: 40px;
      }
      h1 {
        text-decoration: solid;
        color: rgb(198, 124, 64);
        font-size: 4em;
        border: 2px solid rgb(198, 124, 64);
        margin: 0 auto;
        max-width: 800px;
        text-align: center;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        background: rgb(250, 246, 213);
        border-radius: 30px;
        padding: 10px 0;
      }
      h2 {
        font-size: 23px;
        font-weight: lighter;
        text-decoration: none;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        color: rgb(250, 246, 213);
        text-shadow: 0 0 6px rgb(198, 124, 64), 0 0 5px rgb(250, 246, 213);
      }
      img {
        display: block;
        margin: 40px auto;
        -webkit-filter: sepia(70%);
          filter: sepia(70%);
          -webkit-transition: .3s ease-in-out;
          transition: .3s ease-in-out;
          border-radius: 3px;
      }
      img:hover {
          cursor: pointer;
          filter: none;
      }
      p {
          font-size: 25px;
          color:rgb(250, 246, 213);
          display: block;
          margin: 0 auto;
      }
      a {
        color:rgb(78, 40, 1);
        line-height: 10px;
        text-decoration: none;
        font-weight:bolder;
        font-size: smaller;
      }
      a:hover {
        color:rgb(250, 246, 213);
        text-decoration:underline;
        transition: all 900ms ease-out;
      }
      button {
        display: block;
        border-spacing: 20px;
        margin: 50px auto 0;
        color: rgb(250, 246, 213);
        font-size: 20px;
        padding: 15px 20px;
        border: 3px solid rgb(250, 246, 213);
        border-radius: 90px;
         text-shadow: 0 0 6px rgb(198, 124, 64), 0 0 5px rgb(250, 246, 213);
        background: linear-gradient(44.8deg, rgba(255, 136, 102, 0.67) -53.1%, rgba(255, 221, 136, 0.28) 49%);
      }
     
      button:hover {
color: white;
background: linear-gradient(to right, #ffecd2 0%, #fcb69f 100%);
transition: all 400ms ease-in-out;
opacity:2;
border-radius: 50px;
box-shadow: 3px 3px 8px rgb(250, 246, 213);
border: 1px solid rgb(250, 246, 213);
pointer-events:visibleFill;
cursor:pointer;
 text-shadow: 0 0 6px rgb(198, 124, 64), 0 0 5px rgb(198, 124, 64);
      }
      hr {
          display: block;
          border: none;
          background-color:rgb(198, 124, 64);
          height: 2px;
          max-width: 800px;
      }
.signature {
  color:   #685454a9;
  text-align: center;
  margin: 0 auto;
  font-size: 20px;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  margin: 50px;
}
     .author {
       color:rgb(199, 178, 178); 
      text-decoration: solid;
     }
     .author:hover {
       text-decoration: solid;
       transition: 1s;
       color:rgb(78, 40, 1);
     }
    </style>
  </head>
  <body>
    <h1>Corgi</h1>
    <h2> <strong>Smart/Alert/Affectionate </strong> </br>
    A friend you need</h2>
    <img
      src="https://static.fajnyzwierzak.pl/media/uploads/media_image/original/wpis/672/welsh-corgi-pembroke.jpg"
      alt="Corgi in a garden"
      width="500"
    />
    <hr>
    <p>
      Among the most agreeable of all small housedogs, the Pembroke Welsh Corgi
      is a strong, athletic, and lively little herder who is affectionate and
      companionable without being needy. They are one the world's most popular
      herding breeds. At 10 to 12 inches at the shoulder and 27 to 30 pounds, a
      well-built male Pembroke presents a big dog in a small package. Short but
      powerful legs, muscular thighs, and a deep chest equip him for a hard
      day's work. Built long and low, Pembrokes are surprisingly quick and
      agile. They can be red, sable, fawn, and black and tan, with or without
      white markings. The Pembroke is a bright, sensitive dog who enjoys play
      with his human family and responds well to training. As herders bred to
      move cattle, they are fearless and independent. They are vigilant
      watchdogs, with acute senses and a 'big dog' bark. Families who can meet
      their bold but kindly Pembroke's need for activity and togetherness will
      never have a more loyal, loving pet.
    <hr>
    </p>
    <p>
    <a href="https://www.akc.org/dog-breeds/pembroke-welsh-corgi/">
        Check out the breed traits 
</a>
</p>
      <button>subscribe to
      </br>corgi newsletter</button>
    </p>
    <div class="signature">
      coded by 
      <span class="author">
      Karola
    </span>
    </div>
    <script>
        function contact() {
            let name = prompt("What is your name?");
            let mail = prompt("What is your email adress?");
            let info = prompt("Do you have a corgi?");
            if (info === "no") {
            alert ("Don't worry, " + name + "! You have the access to our newsletter. Now you can discover a world of Corgi!");
        } else {
            alert ("You're so lucky, " + name + "! Check out your mailbox to get to know even better your four-legged friend!");
        }
    }
        let button = document.querySelector("button");
        button.addEventListener("click", contact);
    </script>
  </body>
</html>
