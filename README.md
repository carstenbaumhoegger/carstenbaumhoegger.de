# carstenbaumhoegger.de

## How to update to a new version of Unify

1. replace "assets" folder with "assets" folder from `/One-Pages/Classic`
2. Comment out the following lines in /assets/css/one.style.css
  `.promo-section h2:after,
  .promo-section h2:before {
    font-size: 16px;
    content: "\f005";
    position: absolute;
    font-family: FontAwesome;
    position: absolute;
    top: 50%;
    margin-top: -8px;
  }` (line 666-677)
3. Replace provided jQuery.min with [jQuery 2.2.4](https://code.jquery.com/jquery-2.2.4.min.js)
3. check if all parts of the page work as expected

## How to update Let's Encrypt SSL certificate
https://certbot.eff.org/#ubuntuxenial-apache

Current certificate is valid until 08.12.2016
