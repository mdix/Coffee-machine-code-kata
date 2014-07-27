# Coffee machine code kata
Code a bean-to-cup coffee machine. You can decide how much capacity the watertank has and how much half a cup / a cup is. (Aside: Why? Because I've always wanted to do it.)

## Lights 
* brewing
* heating up
* clean waste container
* refill water
* no beans

## Featues (grinding + brewing = duration until cup is finished)
* grinding (how much coffee)
** strong: 7 seconds
** normal: 5 seconds
** mild: 3 seconds
* brew half a cup, 15 seconds
* brew a cup, 30 seconds
* hot steam to preheat cups (blocks brewing and visa versa)

## Buttons
* on / off (starts heating, heating always takes 20 seconds)
* half a cup / cup (default: half a cup)
* grinding
** pressed once: thin
** pressed twice: normal (default)
** pressed thrice: strong
* steam
* start

So if you turn it on and the heating light shows that it's heated up and you press the start button it would brew half a cup normal coffee. It would take: 20 seconds (heatup) + 5 seconds (grinding) + 15 seconds (brewing) = 40 seconds.


Imagine it as something like the thing shown below:

![Coffee Machine](http://1.bp.blogspot.com/-yGXNyEhVIGw/U9QRFAugLKI/AAAAAAAACi0/T_Z7CGhChzc/s1600/coffeemachine.jpg "Coffee Machine")

have phun!
If you have questions, use comments below. It's the first draft of this kata.