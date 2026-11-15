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
