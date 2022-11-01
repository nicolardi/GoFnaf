# GoFnaf
<pre>
<span style="color: green">
  ____|  _)                            _)           |       |
  |       |  \ \   /    _ \     __ \    |    _` |   __ \    __|    __|
  __|     |   \ \ /     __/     |   |   |   (   |   | | |   |    \__ \
 _|      _|    \_/    \___|    _|  _|  _|  \__, |  _| |_|  \__|  ____/
                                           |___/
</span>
<span style="color: red">
                                @@@@@@  @@@@@@@   @@@@@@@@ @@@@@@@  @@@@@@@@ @@@@@@@  @@@@@@@  @@@ @@@  @@  @@@@@@
                               @@!  @@@   @@!     @@!      @@!  @@@ @@!      @@!  @@@ @@!  @@@ @@! !@@ !@  !@@
                               @!@!@!@!   @!!     @!!!:!   @!@!!@!  @!!!:!   @!@  !@! @!@  !@!  !@!@!       !@@!!
                               !!:  !!!   !!:     !!:      !!: :!!  !!:      !!:  !!! !!:  !!!   !!:           !:!
                                :   : :    :       :        :   : : : :: ::: :: :  :  :: :  :    .:        ::.: :
</span>
*** GO Version
</pre>

This project is just an experiment to learn go language and a tribute to the game Five Nights at Freddy's

# How it works

Just do the following

- run the server
- run the client and play

Once started the server as many clients as you like can connect and play hard

# What's the game about?

[Five Nights at Freddy's](https://en.wikipedia.org/wiki/Five_Nights_at_Freddy's) is an indie videogame which dates back to 2014.

You accept a job at "Freddy Fazbear's Pizza" the main attraction of the location being a set of animatronics.
Your task is to check that everything is fining during the night from midnight to 6AM.
On your first work-day you start to understand that something is wrong. The animatronics wake up during the night and start walking
from one room to another until they reach your office ancd kill you.

You can only do a few basic actions to stay safe: close doors and look at camera's to see where the animatronic are.
But closing the door drains energy from the battery. If it's over the place becomes dark and the doors reset open and you cannot defend yourself anymore.

Are you sure you want to start this nightmare? If so download the sources and start playing!

# How to start the server





a recreation of five night at freddy's as a text game in GO 

## What works
cameras, battery, enemies, doors

## what i still have to fix/implement
1)
Golden freddy, 

2)
someting that most of the times makes you notice that an animatronic is at your door

3)
a versus mode where one player controls the animatronic and the other controls the night guard

## usage
now that the game has an actual game client (if a bit rough) l'll explain how to run the server and the client

### server
you can decide wether to run the server via a docker container or via the .go file without docker,

### docker
to run this image with docker you have to run 


docker run --rm --name gofnafserver -p 8080:8080 -t -d rickytrevor/gofnafdocker

i'll update this image as soon as i publish a new version of the server

Client
you can run the client inside docker if you don't have go installed by running docker run -ti rickytrevor/gofnaf-client

### "standard" way

to run the server in the "standard" you have to build it by going inside the serverside directory and running go build and then go run gofnaf to actually start the server

### client

the procedure is mostly the same, go inside the clientside directory and run go build . and then run the client executable file

### if you want to play the game without hosting an actual client at home

so if you really want to play this "game" i'm hosting a game server on my personal server, you can access it by starting the client and putting as the ip:port

