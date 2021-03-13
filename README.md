# Music Player 

![](https://media.giphy.com/media/xT5LMCzMVpWq1aXrqw/giphy.gif)

This is a Javascript music App of which the user can Search, Delete, and Add music. No dependencies needed.


- After getting to the right dirctory where the file is cloned 

- To run the app you will run several commands. 


    ```
     node pure_code.js
    ```
    The Create a New instance of music player

    ```
    const newSong = new MusicPlayer()
    ```

- Then you call the created instances such at this. 

 
     ```
     newSong.add( "The One" ,"reggie", 1970 )

       console.log(musicPlayer.stack)  

       =>
       [
        { title: 'gone with the wind', genre: 'pop', year: 1940 },
        { title: 'carter 4', genre: 'rap', year: 2000 },
        { title: 'sweet home alabmia ', genre: 'country', year: 1990 },
        { title: 'sweet home OHio ', genre: 'rock', year: 1590 },
        { title: 'Morning Mr Magpie', genre: 'country', year: 1990 },
        { title: 'Lotus Flower', genre: 'gospel', year: 1990 },
        { title: 'Give up the ghost ', genre: 'rock', year: 1990 },
        MusicPlayer { title: 'The One', genre: 'reggie', year: 1970 }
     ]
     ```

 Also you can run 

  To delete music
   ```
     console.log(musicPlayer.delete("home")) 
  ``` 

   To Search Music 
   ```
  musicPlayer.search("sweet") 
  ```
  print out all the music.

  ```
console.log(musicPlayer.stack)  
```

[Author]{samrey2018@gmail.com}

[BLog]{http://techuture.com/}

[Linkedin]{https://www.linkedin.com/in/samuel48/ }

[GitHub]{https://github.com/EPIC448 }