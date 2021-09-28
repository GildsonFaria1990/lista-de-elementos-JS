# lista-de-elementos-JS
#codigo limpo

var listaFilmes = [
  "https://clarovideocdn3.clarovideo.net/PELICULAS/EQUALIZER2THE/EXPORTACION_WEB/PT/EQUALIZER2THEWVERTICAL.jpg?size=200x300]",
  "https://upload.wikimedia.org/wikipedia/pt/2/24/Hoodwinked.jpg",
  "https://upload.wikimedia.org/wikipedia/pt/c/c6/Teo-neol.jpg"
];

for (var i = 0; i < listaFilmes.length; i++) {
  document.write("<img src=" + listaFilmes[i] + ">");
}
