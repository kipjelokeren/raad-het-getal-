let geheimGetal = Math.floor(Math.random() * 100) + 1;
let pogingen = 0;
console.log("Ik heb een getal gekozen tussen 1 en 100. Typ 'raadGetal(jouwGetal)' in de console om te raden!");

function raadGetal(gok) {
    pogingen++;
    if (gok < geheimGetal) {
        console.log("Te laag! ⬆️ Probeer opnieuw.");
    } else if (gok > geheimGetal) {
        console.log("Te hoog! ⬇️ Probeer opnieuw.");
    } else {
        console.log(`🎉 Gefeliciteerd! Je hebt het getal ${geheimGetal} geraden in ${pogingen} pogingen.`);
    }
}
