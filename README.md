# Webdesign

Skip to content
Pull requests
Issues
Marketplace
Explore
@AlmaLaza
AlmaLaza /
Webdesign
Public

1
0

    0

Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights

    Settings

Webdesign/CSS/index.html
@AlmaLaza
AlmaLaza Added initial Alma Webdesign Files
Latest commit 7b39059 3 hours ago
History
1 contributor
89 lines (89 sloc) 3 KB
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Alma Lazarillo</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="icon" href="images/AlinesFavicon.ico" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300&family=Roboto:wght@300&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <div id="hero-banner"></div>
    <div class="top-container">
      <img
        id="profile-picture"
        src="images/Alma Profilbild.png"
        alt="Alma Lazarillo Profilbild"
      />
      <br />
      <h1>
        Ich bin Alma Lazarillo,<br />
        Programmiererin und Webdesignerin.
      </h1>
      <p id="profile-description">
        Bei mir bekommen Sie Webdesign, Content Creation und Webdevelopment aus
        einer Hand.
      </p>
    </div>
    <div class="middle-container">
      <div class="skill-row">
        <img
          class="webdesign"
          src="images/georgie-cobbs-muOHbrFGEQY-unsplash-min (1).jpg"
          alt="Tastatur mit Stift und Screen"
        />
        <h2>Webdesign</h2>
        <p>
          In enger Abstimmung mit Ihnen kreiere ich passgenaue Designs. UX und
          UI stehen dabei für mich im Mittelpunkt.
        </p>
      </div>
      <div class="skill-row">
        <img
          class="content"
          src="images/eduardo-casajus-gorostiaga-ZWIqGpOYqRg-unsplash-min (1).jpg"
          alt="Laptop Kamera Handy und Stifte"
        />
        <h2>Content Creation</h2>
        <p>
          Meine maßgeschneiderten Pakete umfassen Bilder und Texte. So kann ich
          Design und Content aufeinader abstimmen und zu einem überzeugenden
          Endprodukt verschmelzen.
        </p>
      </div>
      <div class="skill-row">
        <img
          class="webdevelopment"
          src="images/markus-spiske-MgtHZ4zlC1U-unsplash(1)-min.jpg"
          alt="Screen mit Code"
        />
        <h2>Webdevelopment</h2>
        <p>
          Gemeinsam finden wir die technisch perfekte Lösung, die Ihren
          Bedürfnissen im Hinblick auf die langfristige Betreuung der Seite
          entspricht.
        </p>
      </div>
      <div class="Kontakt">
        <p>
          Sie möchten eine neue Webseite erstellen lassen oder eine bestehende
          Seite verändern? <br />Kontaktieren Sie mich gerne.<br />
          Ich biete sowohl Standard-Pakete, als auch maßgeschneiderte Lösungen
          für Privatpersonen und Unternehmen an.
        </p>
      </div>
      <a class="BUTTON_ZTF" href="mailto:name@email.com">Kontakt</a>
    </div>
    <div class="bottom-container">
      <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
      <a class="footer-link" href="https://twitter.com/">Twitter</a>
      <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
      <p class="copyright">© 2021 Alma Lazarillo.</p>
    </div>
  </body>
</html>

    © 2021 GitHub, Inc.
    Terms
    Privacy
    Security
    Status
    Docs

    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

Loading complete
body {
  background-color: #fcf8f7;
  font-family: "Roboto", sans-serif;
  font-size: 20px;
  margin: 0;
  text-align: center;
}

h1 {
  color: #131310;
  font-family: "Comfortaa", cursive;
  font-size: 4vh;
  line-height: 2;
  margin: 220px auto 0 auto;
  padding-top: 20px;
  padding-bottom: 20px;
}

h2 {
  color: #445ea0;
  font-size: 2, 5rem;
  font-weight: normal;
}

h3 {
  color: #2f2c27;
  font-size: 2, 5rem;
}

p {
  color: #2f2c27;
  font-size: 2, 5rem;
  padding-bottom: 20px;
}

/**********CLASS SELECTORS****************/

.header-image {
  width: 100%;
  height: auto;
  object-fit: contain;
}

.top-container {
  max-width: auto;
  height: auto;
  position: relative;
}

.middle-container {
  max-width: auto;
  height: auto;
}

.skill-row {
  width: 50%;
  height: auto;
  margin: 40px auto 100px auto;
  text-align: left;
  line-height: 2;
}
.webdesign {
  float: left;
  margin-top: 10px;
  margin-right: 30px;
  margin-bottom: 50px;
  width: 25%;
  height: auto;
}
.content {
  float: right;
  margin-top: 10px;
  margin-bottom: 50px;
  margin-left: 30px;
  width: 25%;
  height: auto;
}

.webdevelopment {
  float: left;
  margin-top: 10px;
  margin-right: 30px;
  margin-bottom: 90px;
  width: 25%;
  height: auto;
}

.Kontakt {
  color: #131310;
  font-size: 2, 5rem;
  line-height: 2;
  margin-top: 300px;
  max-width: auto;
  height: auto;
  text-align: center;
}

.bottom-container {
  background-color: #bcbcbd;
  height: 200px;
  width: auto;
}

.footer-link {
  color: white;
  margin-top: 50px;
  padding-top: 50px;
}
.copyright {
  color: white;
  margin-bottom: 80px;
}

.BUTTON_ZTF {
  margin-top: 40px;
  margin-bottom: 80px;
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
  font-family: Open Sans;
  color: white;
  font-size: 29px;
  font-weight: 100;
  padding: 34px;
  background-color: #bcbcbd;
  -webkit-box-shadow: 1px 1px 20px 0 #000000;
  -moz-box-shadow: 1px 1px 20px 0 #000000;
  box-shadow: 1px 1px 20px 0 #000000;
  border: solid #ffffff 1px;
  text-decoration: none;
  display: inline-block;
  cursor: pointer;
  text-align: center;
}

.BUTTON_ZTF:hover {
  background: #eaebee;
  border: solid #445ea0 1px;
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
  text-decoration: none;
}

/**********ID SELECTORS****************/

#hero-banner {
  background: url(images/Turmgrau.jpg) center center no-repeat;
  background-size: cover;
  height: 500px;
  height: 67vh;
}

#profile-picture {
  display: block;
  size: 4vh;
  size: 13rem;
  margin-top: 30px;
  position: absolute;
  right: 30%;
}

#profile-description {
  color: #131310;
  font-size: 2, 5rem;
  margin-bottom: 0;
}
