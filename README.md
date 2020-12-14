# olorunyomi.github.io<!DOCTYPE html>
<html>
  <head>
    <title>Startup</title>

    <!-- Google Fonts -->
    <link
      href="https://fonts.googleapis.com/css?family=Montserrat"
      rel="stylesheet"
    />

    <!-- Bootstrap CSS from a CDN. This way you don't have to include the bootstrap file yourself -->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />

    <!-- Your own stylesheet -->
    <link rel="stylesheet" type="text/css" href="./style.css" />
  </head>

  <body>
    <div class="container d-flex align-items-center h-100">
      <div class="row">
        <header class="text-center col-12">
          <h1 class="text-uppercase">
            <strong>The Biggest Startup Event Of The Year</strong>
          </h1>
        </header>
        <div class="buffer col-12"></div>
        <section class="text-center col-12">
          <hr />
          <a href="https://mailchi.mp/067a10f5d6fc/startup">
            <button class="btn btn-primary btn-xl">Find out more</button></a
          >
        </section>
      </div>
    </div>
  </body>
</html>

body,
html {
  width: 100%;
  height: 100%;
  font-family: "Montserrat", sans-serif;
  background: url(./header.jpg) no-repeat center center fixed;
  background-size: cover;
  height: 100%;
  overflow: hidden;
}

h1 {
  font-size: 3rem;
  color: #e2dbdb;
  display: flexbox;
}

.buffer {
  height: 10rem;
}

hr {
  width: 65px;
  border-width: 3px;
  border-color: #f05f44;
}

.btn {
  font-weight: 700;
  border-radius: 300px;
  text-transform: uppercase;
}
.btn-primary {
  background-color: rgb(240, 95, 68);
  border-color: #f05f44;
}

.btn-primary:hover {
  background-color: rgba(240, 95, 58, 0.9);
  border-color: rgba(240, 95, 58, 0.9);
  border-width: 4px;
}

.btn-xl {
  padding: 1rem 2rem;
}

