<!DOCTYPE html>
<html lang="es">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />

        <!-- Bootstrap CSS -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
        <style>
            /* vamos a importar una fuente tipográfica desde  */

            @import url("https://fonts.googleapis.com/css2?family=PT+Serif:ital,wght@0,400;0,700;1,400;1,700&display=swap");

            /* vamos a contradecir a Bootstrap, partiendo por la fuente tipográfica y afectando sus variables --> https://getbootstrap.com/docs/5.1/customize/css-variables/  */

            :root {
                --bs-body-font-family: "PT Serif", Georgia, serif;
            }
            /* vamos a ajustar los pesos de algunos títulos a lo que dispone la fuente  */

            h1,
            h2,
            h3,
            h4 {
                font-weight: 400;
            }

            /* vamos a ajustar los pesos de otros títulos y negrita a lo que dispone la fuente  */

            h5,
            h6,
            strong {
                font-weight: 700;
            }

            /* definiré un tamaño del título de primer nivel (h1) que se ajuste según el viewport width --> https://www.yunbitsoftware.com/blog/2017/06/22/viewport-units-css-que-es/ */

            h1 {
                font-size: calc(3rem + 1vw);
            }

            /* repetiré el truco anterior con el título de segundo nivel (h2), que, a diferencia del anterior, puedo ocupar varias veces en la misma página */

            h2 {
                font-size: calc(0.75rem + 1.25vw);
            }

            /* usaré el ">" entre el título se segundo nive (h2) y el lapso en la misma línea (span) --> https://techbrij.com/css-selector-adjacent-child-sibling */

            h2 > span {
                background: rgba(225, 112, 49, 1);
                color: rgba(255, 255, 255, 1);
            }

            /* sigamos con el título de tercer nivel (h3) */

            h3 {
                font-size: calc(1.5rem + 1vw);
            }
        </style>
        <title>Orangutan de Borneo!</title>
    </head>
    <body>
    </style>
          <body>
            </h1>
            <div class="row">
                <div class="col-sm-8 mx-auto">
                    <h2 class="text-center pt-5 fst-italic"><span class="px-3 py-1">Pongo pygmaeus</span></h2>
                    <h1 class="text-center py-4">Orangutan de Borneo</h1>
                    <!--uso https://www.lipsum.com/ para el texto de relleno-->
                    <p class="lead">
                      <div class="mx-auto" style="width: 600px;">
                        Es el mamífero arbóreo más grande del mundo, lo cual lo hace
                        probablemente uno de los simios más fascinantes que aún existen.
                        En lengua malaya orang gutan significa “hombre del bosque”.
</div>

                    </p>


                      <div class="mx-auto" style="width: 600px;">
                      Infografía Fabiola Hernández y Juan Pablo Astorga
                </div>

               <div class="mx-auto" style="width: 600px;">
               <img class="displayed" src="img/intro.png"alt="El mamífero arbóreo más grande del mundo">
               <div class="position-static">
               </div>
               <div class="text-center">
            </div>
         </div>
  <h3 class="text-center pt-6 pb-2">Localización</h3>
  </div>

</div>
</div>
            </div>
            <div class="card-center" style="width: 18rem;"position align= "center">
    <img src="img/borneo.png" class="card-img-center" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
      <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
  </div>
            <div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-withe">malasia</button>
  <button type="button" class="btn btn-withe">Indonesia</button>
  <button type="button" class="btn btn-withe">Brunéi</button>
      </p>
      </div>
        </p>
  <div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-light">Pygmaeus</button>
  <button type="button" class="btn btn-light">Wurmbii</button>
  <button type="button" class="btn btn-light">Morio</button>
</div>
            </div>
        </header>
        <main>
            <section class="container">
                <div class="row">
                    <div class="col-sm-9 mx-auto">
                        </div>

                        <h4 class="text-center pt-5 pb-2">Caracteristicas Formales<br />
                        Machos y hembras
                        </h4>
                        <div class="card" style="width: 18rem";"position-absolute= left">
                       <img src="img/bridas.png" class="card-img-top" alt="organutan dominante">
                       <div class="card-body">
                       <p class="card-text">Solo el macho dominante tiene
protuberancias laterales que se
denominan bridas</p>
                      </div>
                      </div>
                      <div class="card" style="width: 18rem";"position-absolute= right">
                      <img src="img/sinbridas.png" class="card-img-top" alt="los machos que no las poseen se integran con las hembras">
                     <div class="card-body">
                   <p class="card-text">Los machos que no las poseen se integran con las hembras>
                   </p>
        </div>
    </div>
    </div>
          </div>
              <div class="col-sm-11 mx-auto">

              </div>
            </p>
              </div>

                        <h4 class="text-center pt-5 pb-2">
                            Caracteristicas<br />
                        formales
                      </h4>
                        <img src="img/orangutan.png" alt="describa lo que se ve en la imagen" class="w-60" />
                    </div>
                    <div class="col-sm-9 mx-auto">
                        <h3 class="text-center pt-5 pb-2">Costumbres</h3>
                        <img src="img/nido.jpg" alt="describa lo que se ve en la imagen" class="w-60"/>
                    </div>
                </div>
            </section>
            <section>
                <div class="container-fluid g-0">
                    <div class="row g-0">
                        <div class="col-sm-12 mx-auto">
                            <h3 class="text-center pt-5 pb-2">desplazamiento</h3>
                                </p>
                                </div>
                                  </div>
                                  <div class="mx-auto" style="width: 200px;">
                                <img src="img/des01.png" class="rounded float-start" alt="...">
                                <img src="img/des01.png" class="rounded float-middle" alt="...">
                                <img src="img/des01.png" class="rounded float-next" alt="...">
                        </div>
                      <h3 class="text-center pt-5 pb-2">Turberas</h3>
                        <div class="mx-auto" style="width: 200px;">
                      <img src="img/turberas.png"class="rounded mx-auto d-block" alt="captura co2">

                    </div>
                    <h3 class="text-center pt-5 pb-2">Territorio</h3>

                    <img src="img/territorio.png" class="rounded mx-auto d-block"  alt="...">
                </div>
                <div class="container">
                    <div class="row">
                        <div class="col-sm-9 mx-auto">
                            <div class="row pt-3 pb-5">
                                <div class="col-sm-12 py-2"><h5>Simbología</h5></div>
                                <div class="col-sm-4 py-2">
                                    <dl class="row d-flex align-items-center">
                                        <dt class="col-3"><img src="img/1x1.png" class="w-100"></dt><dd class="col-9"><small>Loren ipsum</small></dd>
                                    </dl>
                                </div>
                                <div class="col-sm-4 py-2">
                                    <dl class="row d-flex align-items-center">
                                        <dt class="col-3"><img src="img/1x1.png" class="w-100"></dt><dd class="col-9"><small>Loren ipsum</small></dd>
                                    </dl>
                                </div>
                                <div class="col-sm-4 py-2">
                                    <dl class="row d-flex align-items-center">
                                        <dt class="col-3"><img src="img/1x1.png" class="w-100"></dt><dd class="col-9"><small>Loren ipsum</small></dd>
                                    </dl>
                                </div>
                                <div class="col-sm-12 py-2">
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. In tellus eros, efficitur a eros at, eleifend rutrum est. Proin dolor nisl, hendrerit in dapibus vitae, molestie eu magna. Mauris at erat
                                        neque. Nulla ut convallis elit. Donec venenatis quam quam, quis facilisis sapien ultricies ac. Proin ut commodo nibh, non bibendum dui. Vestibulum convallis efficitur metus, vel vestibulum libero
                                        interdum quis. Ut varius sagittis sapien eget cursus. Morbi accumsan lectus nec sapien fermentum, a vestibulum nisl tempus. Pellentesque mollis nulla orci, id lobortis magna egestas quis. Nunc
                                        molestie, purus a posuere dapibus, turpis orci ornare elit, in semper dui purus sed nulla. Aenean vitae pharetra sem. Etiam consequat urna a lorem efficitur, vitae venenatis nisl rutrum. Aliquam
                                        dictum libero porttitor tellus consequat malesuada. Vivamus rhoncus ante ut libero pellentesque, luctus consectetur orci ultrices.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container-fluid g-0">
                    <div class="row g-0">
                        <div class="col-sm-12">
                            <h3 class="text-center pt-5 pb-2">Familia</h3>
                            <img src="img/2x1.png" alt="describa lo que se ve en la imagen" class="w-100" />
                        </div>
                        <div class="col-sm-8 py-5 mx-auto">
                            <p class="px-2">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. In tellus eros, efficitur a eros at, eleifend rutrum est. Proin dolor nisl, hendrerit in dapibus vitae, molestie eu magna. Mauris at erat neque. Nulla
                                ut convallis elit. Donec venenatis quam quam, quis facilisis sapien ultricies ac. Proin ut commodo nibh, non bibendum dui. Vestibulum convallis efficitur metus, vel vestibulum libero interdum quis. Ut varius
                                sagittis sapien eget cursus. Morbi accumsan lectus nec sapien fermentum, a vestibulum nisl tempus. Pellentesque mollis nulla orci, id lobortis magna egestas quis. Nunc molestie, purus a posuere dapibus,
                                turpis orci ornare elit, in semper dui purus sed nulla. Aenean vitae pharetra sem. Etiam consequat urna a lorem efficitur, vitae venenatis nisl rutrum. Aliquam dictum libero porttitor tellus consequat
                                malesuada. Vivamus rhoncus ante ut libero pellentesque, luctus consectetur orci ultrices.
                            </p>
                        </div>
                    </div>
                </div>
            </section>
            <footer class="bg-dark text-white-50">
                <div class="container">
                    <div class="row">
                        <div class="col py-5">
                            <p class="text-center small">Lo dejaremos hasta aquí, por ahora</p>
                        </div>
                    </div>
                </div>
            </footer>
        </main>
    </body>
</html>
