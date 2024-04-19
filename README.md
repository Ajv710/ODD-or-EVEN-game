# ODD-or-EVEN-game
A game using swing in appache netbeans

A simple game using swing components.Here you get 10 chances,within the given number of chances you have to correctly guess whether the number is even or odd.Ultimately you will get  score out of 10.

working:
1)there are two buttons odd and even , a number label and a score label.
2)the random number generated at number label is taken by the corresponding actionlistener
  a)for instance lets take the number is 79 and odd button is pressed
  b)count=count+1
  c)then odd buttons actionlistener checks whwther the number is odd,if it is odd score=score+1
  d)then a new random number is generated and that is set to the number label and then again user press anyone of the button
  e)if count=10 then score+=1 and a dialog box displayed showing your score
3)stop
