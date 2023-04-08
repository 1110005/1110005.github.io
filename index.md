Space invaders
==============

Discription
-----------
This is a game that aliens anvading Earth,they killed all the army from the peoples,except one.
You are the only soldier that is alive.The peoples founded that aliens all land to Earth from a place,so you--the only soldier,are going to sheild the Earth,
the Earths desteny is in your hand!!
-Use A,W to move
-Press Space to shoot

Features
--------


Intresting code
---------------
This is how the aliens move--
~~~python
    def on_update(self, dt):
        target = waypoints[self.index]
        self.point_toward(target)
        self.move_forward(5)
        if self.distance_to(target)<20:
            self.index+=1
        if self.index >=len(waypoints):
            self.delete()
~~~

Method
------


Resources
---------
-Python/Pycat
-[Kenny Assets](https://www.kenney.nl/assets)
-
-






