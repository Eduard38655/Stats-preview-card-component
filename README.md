# Stats-preview-card-component
Any comments will be appreciated

//HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Stats preview card component</title>
    <link rel="stylesheet" href="CSS.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@900&display=swap"
      rel="stylesheet" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap"
      rel="stylesheet" />
  </head>
  <body>
    <main>
      <aside>
        <div class="container">
          <p>Get <span>insights</span> that help your business grow. </p>
          <p>
            Discover the benefits of data analytics and make better decisions
            regarding revenue, customer experience, and overall efficiency.
          </p>
        </div>

        <div class="info-rate">
          <p> 10k+ <span>companies</span> </p>
          <p>314 <span>templates</span> </p>
          <p>12m+ <span>queries</span> </p>
        </div>
      </aside>
      <div class="imagen-sec">
        <img
          src="Imagen/image-header-desktop-stats-preview-card-component-main.jpg"
          alt="" />
      </div>
    </main>

    <script src="JavaScript.js"></script>
  </body>
</html>


//CSS


* {
  margin: 0;
  padding: 0;
}
body {
  width: 1440px;
  height: 800px;
  background-color: hsl(233, 47%, 7%);
  display: flex;
  justify-content: center;
  align-items: center;
}

main {
  width: 1115px;
  height: 443px;
  background-color: hsl(244, 38%, 16%);
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: start;
  border-radius: 10px 10px 10px 10px;
}
aside {
  width: 572px;
  height: 435px;
  display: flex;
  justify-content: center;
  flex-direction: column;

  justify-content: space-around;
}
aside > .container {
  width: 344px;
  height: 220px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  justify-content: space-evenly;
  text-align: center;
}
aside > .container > p:nth-child(1) {
  font-size: 30px;
  font-family: "Inter", sans-serif;
  color: hsl(0, 0%, 100%);
}
aside > .container > p:nth-child(1) > span {
  color: hsl(277, 64%, 61%);
  font-family: "Inter", sans-serif;
}
aside > .container > p:nth-child(2) {
  color: hsla(0, 0%, 100%, 0.6);
  font-family: "Lexend Deca", sans-serif;
  font-size: 15px;
}
aside > .info-rate {
  font-size: 20px;
  display: grid;
  width: 440px;
  height: 50px;
  align-items: start;
  font-family: "Inter", sans-serif;
  color: hsl(0, 0%, 100%);
  justify-content: space-around;
  grid-template-columns: 80px 80px 90px;
}
aside > .info-rate > p > span {
  font-size: 15px;
  color: hsla(0, 0%, 100%, 0.6);
  font-family: "Lexend Deca", sans-serif;
}

.imagen-sec {
  height: 443px;
  width: 545px;
  display: flex;
  justify-content: end;
  align-items: end;
  background-color: hsl(277, 74%, 51%);
  margin-right: -119px;
  border-radius: 0px 10px 10px 0px;
}
.imagen-sec > img {
  height: 443px;
  width: 545px;
  opacity: 0.5;
  border-radius: 0px 10px 10px 0px;
}

@media (max-width: 375px) {
  * {
    margin: 0;
    padding: 0;
  }
  body {
    width: 375px;
    height: 956px;
    background-color: hsl(233, 47%, 7%);
    display: flex;
    justify-content: center;
    align-items: center;
  }

  main {
    width: 333px;
    height: 785px;
    background-color: hsl(244, 38%, 16%);
    display: flex;
    flex-direction: column-reverse;
    justify-content: center;
    align-items: start;
    border-radius: 15px 15px 15px 15px;
  }
  aside {
    width: 329px;
    height: 545px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
  }
  aside > .container {
    width: 290px;
    height: 265px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    justify-content: space-evenly;
    text-align: center;
  }
  aside > .container > p:nth-child(1) {
    font-size: 30px;
    font-family: "Inter", sans-serif;
    color: hsl(0, 0%, 100%);
  }
  aside > .container > p:nth-child(1) > span {
    color: hsl(277, 64%, 61%);
    font-family: "Inter", sans-serif;
  }
  aside > .container > p:nth-child(2) {
    color: hsla(0, 0%, 100%, 0.6);
    font-family: "Lexend Deca", sans-serif;
    font-size: 16px;
  }
  aside > .info-rate {
    font-size: 20px;
    display: grid;
    width: 327px;
    height: 245px;
    font-family: "Inter", sans-serif;
    color: hsl(0, 0%, 100%);

    justify-content: space-evenly;

    grid-template-columns: 40px;
  }

  aside > .info-rate > p > span {
    font-size: 16px;

    color: hsla(0, 0%, 100%, 0.6);
    font-family: "Lexend Deca", sans-serif;
  }

  .imagen-sec {
    height: 243px;
    width: 333px;
    display: flex;
    justify-content: end;
    align-items: end;
    border-radius: 15px 15px 0px 0px;

    background-color: hsl(277, 74%, 51%);
  }
  .imagen-sec > img {
    height: 243px;
    width: 333px;
    opacity: 0.5;
    border-radius: 15px 15px 0px 0px;
  }
}

