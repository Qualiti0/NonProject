I'm bored right now.
```
am_i_bored ? {
  print("i guess i need to work");
  should_i_work ? {
    work_time = true
  } : {
    print("okay i don't know what to do. should i play a game?");
    play_a_game ? {
      print("alright. what game should we play, osu?");
      play_osu ? {
        print("okay. i'll play osu. cya")
      } : {}
    } : {
      print("okay then. cya.")
    }
  }
} : {}
```
