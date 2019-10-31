<template>
  <div class="app">
    <body>
      <header>
        <!-- this is navbar, comment it out if u wanna add bookoo navbar-->
        <nav class="navbar navbar-inverse navbar-fixed-top">
          <div class="container">
            <div class="navbar-header">
              <button type="button" class="navbar-toggle collapsed">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
              </button>
            </div>

            <div class="navbar-collapse">
              <ul class="nav navbar-nav navbar-right">
                <li>
                  <a
                    href="./index.html#contact-section-container"
                    title=""
                    class="anchor-link"
                    >Contact Us</a
                  >
                </li>
                <li>
                  <p>
                    <a
                      href="./components.html"
                      class="btn btn-default navbar-btn"
                      >Home</a
                    >
                  </p>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </header>
      <!-- navbar ends here-->

      <!--background image and text -->
      <div class="background-image-container meow"><!-- refer meow in css for image link -->
        <div class="overlay"></div>
        <div class="container">
          <div class="row">
            <div class="col-xs-12">
              <h1>Donate Books in 1 Minute</h1>
              <h3 class="">
                Fill the form we will collect from home<br />
                Share the gift of knowledge
              </h3>
              <p style="font-weight: bold;color:black" >
                There are more than 7 crore students in India and 30% of them
                does not have access to quality education. It's time to take the
                action and donate your used books to help these unprivileged
                kids. Books you throw in garbage or sell to raddiwala can be
                easily donated to these kids which will help in shaping their
                future.
              </p>
              <a
                href="#contact-section-container"
                class="btn btn-primary btn-lg anchor-link"
                title=""
                >Donate</a
              >
              <h3
              >What we accept</h3>
              <ul>
                <li class='donate'>School Books</li>
                <li class='donate'>Board Games</li>
                <li class='donate'>Story Books</li>
                <li class='donate'>College Books</li>
                <li class='donate'>Fresh Stationery</li>
                <li class='donate'>Other Books</li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <!-- bookoo symbol -->
      <div class="section-container">
        <div class="container">
          <div class="row">
            <div class="col-xs-12 col-md-12 section-container-spacer">
              <h2 class="text-center">AN INITIATIVE BY</h2>
            </div>
          </div>
          <div>
            <img src="./assets/bookoo.png"  class="bookoo">
          </div>
        </div>
      </div>

      <hr style="border:0.3px solid black;">

      <div>
        <img src="./assets/images/proc.png"  class="process"><!--add the process html -->
      </div>

      <!--A THE CODE OF NUMBER OF BOOKS DONATED-->

      <hr style="border:0.3px solid black;">

      <!-- HERE U CAN ADD NGO PARTNERS -->
      <div class="section-container">
        <div class="container">
          <div class="row">
            <div class="col-xs-12 col-md-12 section-container-spacer">
              <h2 class="text-center">NGO Partners</h2>
            </div>
          </div>
          <div class="row">
            <div class="col-xs-12 col-md-4">
              <div class="zoom">
                <img
                  src="./assets/images/img-02.png"
                  alt=""
                  class="center img-responsive"
                />
                <h3 class="text-center">The Robin Hood Army</h3>
                <p>
                  The Robin Hood Army is a volunteer based, zero-funds organization that works to get surplus food from restaurants and the community to serve less fortunate people.
                </p>
              </div>
            </div>

            <div class="col-xs-12 col-md-4 zoom">
              <img
                src="./assets/images/img-03.jpg"
                alt=""
                class="img-responsive"
              />
              <h3 class="text-center">Malesuada</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                sit amet consectetur dolor. Phasellus ut lacus tellus. In
                pretium lobortis blandit.
              </p>
            </div>
            <div class="col-xs-12 col-md-4 zoom">
              <img
                src="./assets/images/img-04.jpg"
                alt=""
                class="img-responsive"
              />
              <h3 class="text-center">Phasellus</h3>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                sit amet consectetur dolor. Phasellus ut lacus tellus. In
                pretium lobortis blandit.
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="section-container" id="contact-section-container">
        <div class="container contact-form-container">
          <div class="row">
            <div class="col-xs-12 col-md-offset-2 col-md-8">
              <div class="section-container-spacer">
                <h2 class="text-center">Get in touch</h2>
              </div>
              <form action="">
                <div class="row">
                  <div class="col-md-6">
                    <div class="form-group">
                      <input
                        type="text"
                        name="name"
                        class="form-control"
                        placeholder="Name"
                      />
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="form-group">
                      <input
                        type="email"
                        name="email"
                        class="form-control"
                        placeholder="Email"
                      />
                    </div>
                  </div>
                </div>

                <div class="form-group">
                  <textarea
                    class="form-control"
                    rows="3"
                    placeholder="Enter your message"
                  ></textarea>
                </div>

                <div class="form-group">
                  <label class="checkbox-inline">
                    <input
                      type="checkbox"
                      id="inlineCheckbox1"
                      value="option1"
                    />Email me a copy
                  </label>
                  <label class="checkbox-inline">
                    <input
                      type="checkbox"
                      id="inlineCheckbox2"
                      value="option2"
                    />I am a human
                  </label>
                </div>

                <button type="submit" class="btn btn-primary">
                  Send message
                </button>
                <a href="" class="btn btn-default">Reset</a>
              </form>
            </div>
          </div>
        </div>
      </div>
      <div>
        <img src="./footer.png"  class="process"> <!--add the original bookoo footer -->
      </div>
    </body>
  </div>
</template>
