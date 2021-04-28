<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Profile card component</title>

    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style/style.css" type="text/css" />
  </head>
  <body>
    <img src="images/bg-pattern-top.svg" class="top svg" alt="" srcset="" />
    <img
      src="images/bg-pattern-bottom.svg"
      class="bottom svg"
      alt=""
      srcset=""
    />
    <main class="card">
      <header><img src="images/bg-pattern-card.svg" alt="" srcset="" /></header>
      <section class="info">
        <img
          src="images/image-victor.jpg"
          alt="profile image of the user"
          class="profile-pic"
        />
        <section class="info-text">
          <p class="name">Victor Crest <span>26</span></p>
          <p class="city">London</p>
        </section>
      </section>
      <hr />
      <footer>
        <p>80K <span>Followers</span></p>
        <p>803K <span>Likes</span></p>
        <p>1.4K <span>Photos</span></p>
      </footer>
    </main>
    <!--   <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Your Name Here</a>.
    </div> -->
  </body>
</html>
