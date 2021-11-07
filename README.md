# tokenconnetor
Ce connecter à un token discord via a navigateur de recherche 




- Allez sur discord https://discord.com/login
- faire F12 
- Allez dans la console

Puis suivais les étapes suivante

Etape 1 : 


function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
} 


Etapes 2 : 

Login(votre token) 

voila c'est bon

