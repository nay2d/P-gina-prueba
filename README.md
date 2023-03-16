# P-gina-prueba
# Html y CSS
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <title>Document</title>
    <style>
      #heading { color: #ffffff; }

      * {
        box-sizing: border-box;
        margin: 0px;
        padding: 0px;
      }
      .header-container {
        background-color: #f44336;
        color: #ffff;
        text-align: center;
        padding: 128px 16px;
      }
      .header-container .header__title {
        margin: 16px;
        font-size: 64px;
      }
      .header-container .header__text {
        margin: 16px;
        font-size: 24px;
      }
      .header-container .button {
        display: inline-block;
        vertical-align: middle;
        overflow: hidden;
        text-align: center;
        cursor: pointer;
        white-space: nowrap;
        margin-top: 16px;
        padding: 12px 24px;
        background-color: #000;
        color: #ffff;
        border: none;
        font-size: 18px;
      }
      .grid-container {
        max-width: 980px;
        margin-left: auto;
        margin-right: auto;
        padding-top: 64px;
        padding-bottom: 64px;
      }

      .grid-container .content {
        display: flex;
        flex-direction: row;
      }

      .content .__twothird {
        width: 66.66666%;
      }
      .twothird h1,
      .__twothird h1 {
        font-weight: 400;
        margin: 10px 0;

        font-size: 36px;
      }
      .twothird h5,
      .__twothird h5 {
        font-size: 18px;
        font-weight: 400;
        margin: 10px 0;
        padding-top: 16px;
        padding-bottom: 16px;
      }
      .twothird p,
      .__twothird p {
        font-size: 15px;
        font-weight: 400;
        line-height: 1.5;
        color: #757575;
      }
      .content .third {
        width: 33.33333%;
        font-size: 15px;
        line-height: 1.5;
        text-align: center;
      }
      .content .third i {
        color: #f44336;
        font-size: 200px;
        padding-top: 64px;
        padding-bottom: 64px;
      }
      .grid-container_two {
        margin-left: auto;
        margin-right: auto;
        padding-top: 64px;
        padding-bottom: 64px;
      }
      .grid-container_two .content {
        max-width: 980px;
        display: flex;
        flex-direction: row;
        margin: 0px auto;
      }
      .gray {
        color: #000;
        background-color: #f1f1f1;
      }
      .second-grid .w3-third {
        width: 33.33333%;
        text-align: center;
      }
      .second-grid .twothird {
        width: 66.66%;
      }
      .second-grid .w3-third i {
        font-size: 200px;
        color: #f44336;
        padding-top: 64px;
        padding-bottom: 64px;
        margin-right: 16px;
      }
      .info-container {
        color: #fff;
        background-color: #000;
        padding-top: 64px;
        opacity: 0.6;
        padding-bottom: 64px;
        text-align: center;
      }
      .info-container h1 {
        margin: 16px;
        font-weight: 400;
      }
      .footer {
        padding-top: 64px;
        padding-bottom: 64px;
        text-align: center;
        font-size: 15px;
        line-height: 1.5;
        opacity: 0.6;
      }
      .footer .footer-container {
        padding-top: 32px;
        padding-bottom: 32px;
        font-size: 24px;
      }

      #navlist { padding: 3px 0px;
      
      border-bottom: 1px solid #000000;
      background-color:#fe2919;
      font: bold 16px sans-serif; }

      #navlist li { list-style: none; display: inline; margin-left:0px;}

      #navlist li a { padding: 4px 1em;
      background: #fe2919; text-decoration: none; }

      #navlist li a:link { color: #f44336; }
      #navlist li a:hover {color: #000000; background: rgb(255, 255, 255); border-color: rgb(0, 0, 0); }
      #navlist li a#current { background: rgb(0, 0, 0); }
    </style>
  </head>
  <body>
    <div id="navcontainer">
      <ul id="navlist">
        <li><a href="" id="heading">Home</a></li>
        <li><a href="" id="heading">Link1</a>
        <li><a href="" id="heading">Link2</a>
        <li><a href="" id="heading">Link3</a></li>
        <li><a href="" id="heading">Link4</a></li> 
      </ul>
    </div>
    <!-- Header -->
    <header
      class="header-container header-red header-center"
      style="padding: 128px 16px"
    >
      <h1 class="header__title">START PAGE</h1>
      <p class="header__text">Template by w3.css</p>
      <button class="button">Get Started</button>
    </header>

    <!-- First Grid -->
    <div class="grid-container">
      <div class="content">
        <div class="__twothird">
          <h1>Lorem Ipsum</h1>
          <h5 class="w3-padding-32">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat.
          </h5>

          <p class="w3-text-grey">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Excepteur sint occaecat cupidatat
            non proident, sunt in culpa qui officia deserunt mollit anim id est
            laborum consectetur adipiscing elit, sed do eiusmod tempor
            incididunt ut labore et dolore magna aliqua. Ut enim ad minim
            veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>

        <div class="third">
          <i class="fa fa-anchor w3-padding-64 w3-text-red"></i>
        </div>
      </div>
    </div>

    <!-- Second Grid -->
    <div class="grid-container_two gray">
      <div class="content second-grid">
        <div class="w3-third w3-center">
          <i class="fa fa-coffee w3-padding-64 w3-text-red w3-margin-right"></i>
        </div>

        <div class="twothird">
          <h1>Lorem Ipsum</h1>
          <h5 class="w3-padding-32">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat.
          </h5>

          <p class="w3-text-grey">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Excepteur sint occaecat cupidatat
            non proident, sunt in culpa qui officia deserunt mollit anim id est
            laborum consectetur adipiscing elit, sed do eiusmod tempor
            incididunt ut labore et dolore magna aliqua. Ut enim ad minim
            veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>
      </div>
    </div>

    <div class="info-container">
      <h1 class="w3-margin w3-xlarge">Quote of the day: live life</h1>
    </div>

    <!-- Footer -->
    <footer class="footer">
      <div class="footer-container">
        <i class="fa fa-facebook-official w3-hover-opacity"></i><a href="https://www.facebook.com/"></a>
        <i class="fa fa-instagram w3-hover-opacity"></i>
        <i class="fa fa-snapchat w3-hover-opacity"></i>
        <i class="fa fa-pinterest-p w3-hover-opacity"></i>
        <i class="fa fa-twitter w3-hover-opacity"></i>
        <i class="fa fa-linkedin w3-hover-opacity"></i>
      </div>
		<p>Powered by <a href="https://www.w3css.com" target="_blank">w3.css</p>
    </footer>
  </body>
</html>
