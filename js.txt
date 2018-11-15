//var seconden = 0;

//function Delayplay(delay){

//  if (seconden == delay)
//  {
//    var intro_song = new Audio("StarWarsThemeSong.ogg");
//    intro_song.play()
//  }
//}

//function incrementSeconds(){
//  seconden +=1;
//}

//var cancel = setInterval(incrementSeconds, 1000);


function delay(){
  var audioPlayer = document.getElementById("audio");
  setTimeout(function() { audioPlayer.play(); }, 10000);
}
