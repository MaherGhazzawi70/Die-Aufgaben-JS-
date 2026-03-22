# Die-Aufgaben-JS-
Aufgabe 1 : Hier habe ich einfach eine Funktion in JS gemacht function addieren(a,b) { return a + b } 

Aufgabe 2 : Hier habe ich eine wurfel Funktion gemacht, da ich es häufig benutzen werde. Danach habe ich 3 Variabeln Wahl und sechser und versuch. ich habe es oben deklariert, um eine klare Struktur zu haben. Ich habe einen promt und switch um Teil 6 zu machen und alle Teile miteinander zu verbinden. ich habe Math.floor und Math.random für den Würfel benutzt. Hier geht es nur um Conditionen also if(ergebnis === 6) sechser++ . wenn das Ergebnis genau 6 ist, dann sechser++ wir haben ein sechser und dann sollte ich versuchen bis ich zwei gleiche Werte habe. Also while(w1 !== w2) bleib daran. Danach sollte ich prüfen, wie viele verscuhe, um einen sechser zu erhalten, wenn ich 2 Würfel habe. Hier habe ich while( x !== 6 && y !== 6) mach weiter ich könnte (x === 6 || y === 6) benutzen, aber die ist einfach. Ich wollte einen neuen Weg versuchen. 

Aufgabe 3 : Die ToDo List hat eine Demo Version https://maherghazzawi70.github.io/Todo-List/ genau wie die Aufgabe verlangt eine a mit Checkbox ich habe diese Logik benutzt und hier ist Code Version : https://github.com/MaherGhazzawi70/Todo-List/blob/main/script.js Gemini hat nur den Code organisiert, da es viel Chaos gab, allerdings kann ich alles verstehen. let data = JSON.parse(localStorage.getItem("todos")) || [];  Das ist für die Localstorage wenn es Daten dort gibt, dann er zeigt die Daten wenn nicht, leer. data.forEach(text => renderTodo(text));
Hier für jede element in data diese Funktion geben. Einen Event für form und  e.preventDefault(); damit die Seite kein Refresch macht. 
 localStorage.setItem("todos", JSON.stringify(data)); Hier speichere ich die Daten als String in Localstorage und die Funktion macht ein li Element und HTML Teil also Checkbox,a,li..... 

 Aufgabe 4 : Diese Teil war die beste Teil, da ich API liebe. Ich habe greeting.json gemacht und ein fetch gemacht, um die Daten anzurufen zuerst habe ich einen Log gemacht also fetch("greeting.json").then(response => response.json()).then( data => console.log(data) dann hier habe ich Schritt für Schritt gearbeitet 1.Daten testen und versuchen die Elemente anzurufen. data.firstname und data.salutation.... let array = [element1,element2,element3]; Ich weiß nicht warum, ich das getan, aber ich fand, es perfommant und dann alle Elemente in gleiche div  let p = document.createElement("p");
        p.innerText = textInhalt;
        Newdiv.appendChild(p);  
Am Ende habe ich es mit CSS gemacht und das Ergebnis erreicht. 

Aufgabe 5 : Diese Aufgabe habe ich nicht fertig gemacht ich habe nur 50% abgeschlossen es fehlt nur Teil B ich hatte nicht verstanden wie ich Todo List mit diese Datei verbinden sollte. 
