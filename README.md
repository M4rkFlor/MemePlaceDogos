# MemePlaceMongo
Created using node js deployed with heroku.<br />
Because Heroku has an ephemeral file system the older version [MemePlace](https://github.com/M4rkFlor/MemePlace "https://github.com/M4rkFlor/MemePlace")(Uses flatfile as DB making it faster!!!) would lose<br />
the users data after herokus web dyno went to sleep(15 mins after no use).<br />
To Save the users data I instead used mLab/MongoDB
The Stucture between MemePlace and MemePlaceMongo is very different therefore I have created two seperate repositories.
Also This version Uses an API to ensure Only Dogs are uploaded.
view the New website that saves your data [Here](https://meme-place-dogos.herokuapp.com "https://meme-place-dogos.herokuapp.com").
