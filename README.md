# wk_logo

## En: a simple way to display logo on the screen.
## Fr: Un Moyen simple de faire apparaitre un logo a l'écran.

## Installation

Place wk_logo" folder in the resource

## Configuration
Open "config.js" and place the link of your logo in logo variable.

# Example
```javascript
// Bienvenue dans la configuration du logo.
// Welcome in the config file for the logo.

logo = "http://myserver.com/mylogo.png" // Lien du Logo -- Link of the logo

// ---------------------
load();

function load() {
	document.getElementById('logo').src = logo;
}
```
