# web-programiranje

na mapi template:
npm install
npx vite/npm run vite
--> mora ispisati local:  http://localhost:8080

na mapi server: 
npm install nodemon
npm run nodemon
--> mora ispisati server is running on http://localhost:3000

bootstrap:
 https://getbootstrap.com/docs/5.3/getting-started/introduction/ -ljepse raspisano za text edit

 https://getbootstrap.com/docs/6.0/getting-started/install/

za razmake
 https://getbootstrap.com/docs/5.3/utilities/spacing/


 brisanje node_modules:
 u mapu template dodji u termilanu i napisi:
 rm -rf node_modules server/node_modules

 provjeri jel nes ostalo:
 find . -name node_modules -type d

zipanje mape:
cd ..

zip -r prezime_ime_kolokvij_1.zip template \
  -x "*/node_modules/*" \
  -x "*/.DS_Store"


  -->ako ne postoji server mapa i moras ju stvorit(pise u v3):
  1. u template dodaj mapu server
  2. otvori ju u terminalu
  3. npm init -y
  4. npm install express nodemon
  5. dodaj ovo: "nodemon": "nodemon index.js"
  6. promijeni type u module
  7. stvori file todos.js i u njega stavi neki predlozak sto imas+ export default todos
  8. stvori file index.js->u njega stavljas stvari iz p3 i editas neke male stvari koje treba
  9. u mapi server npm run nodemon

->bootstrap icons: 
odi gore na icons, pa documentation, u readme github pise:
npm i bootstrap-icons, to kopiraj u terminalu u serveru
i u scss dodaj ovo:
$bootstrap-icons-font-dir: "bootstrap-icons/font/fonts";
@import "bootstrap-icons/font/bootstrap-icons";

-->jquery:
u template npm install jquery
i onda u klijentu u js u script.js:
import $ from "jquery";

link za margine i te udaljenosti:
https://getbootstrap.com/docs/5.3/utilities/spacing/

ako kaze instanciraj instancu klase:
import { Modal } from "bootstrap";
const myModal = new Modal(document.getElementById("editModal"));  //kopiras s bootstrapa

-->promijeni boju pozadine: sccs: $body-bg: 
