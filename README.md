#app{":class" => "{'pressed': pressed}"}
  %audio{:controls => "", :crossorigin => "anonymous", :style => "display: none;"}
    %source{:src => "https://assets.codepen.io/217233/ktkBgAudio.mp3", :type => "audio/mp3"}
  .game
    .game_lose{":class" => "{'show': gameover}"}
      .inner
        %h1 YOU RAN OUT OF TIME!
        %p King Trost was victorious. Refresh to try again.
        %p 
          Be sure to 
          %a{:href => 'https://www.codepen.io/jcoulterdesign'} follow me on Codepen 
          for more pointless stuff.
    .game_win{":class" => "{'show': gamewin}"}
      .inner
        %h1 YOU WIN!
        %p King Trost was slain. Congratulations!
        %p 
          Be sure to 
          %a{:href => 'https://www.codepen.io/jcoulterdesign'} follow me on Codepen 
          for more pointless stuff.
    .game_intro{":class" => "{'gamestarted': gameStarted}"}
