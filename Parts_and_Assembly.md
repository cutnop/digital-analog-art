
---

# Parts List #

  * [OWI Robotic Arm Edge](http://www.amazon.com/OWI-OWI-535-Robotic-Arm-Edge/dp/B0017OFRCY/ref=sr_1_1?ie=UTF8&qid=1366682091&sr=8-1&keywords=owi+robot)
  * 3x [Small 10k Potentiometer](http://www.radioshack.com/product/index.jsp?productId=2062301)
  * [10k Potentiometer](http://www.radioshack.com/product/index.jsp?productId=2062287)
  * Arduino Mega
  * [Adafruit motor shield](http://www.adafruit.com/products/81)
  * Perf-board
  * Thin metal wire that wont bend easily(used to turn pots)
  * Three nuts or other kind of loops
  * Metal rectangular strip (used to mount the larger pot)
  * 5x Push buttons and resistors
  * 5 volt external power supply for the motor shield


---

# Assembly #


**See the "PICTURES" link for additional help**

  1. Assemble OWI robotic arm as per instructions
  1. Mount the three smaller potentiometers to the joints of the arm
    1. Cut the perf-board into three small rectangle's
    1. Solder one potentiometer to each perf-board
    1. Solder three wires to the potentiometer (one for each pin on the pot). Make sure the wires are long enough to span the length of the arm and reach the arduino and motor shield.
    1. Attach a piece of the metal wire to the rotational part of the pot
    1. Glue one perf-board to each of the joints
    1. Glue one nut to each arm with the wire from each pot going through
  1. Mount the bigger potentiometer to the base of the robot
    1. Solder three wires to the pot, as before
    1. Glue the pot to the center of the base
    1. Attach the metal rectangular strip from the rotational part of the pot to the base (a part that doesn't rotate with the robot)
  1. Attach the motor shield to the mega
  1. Wire the base motor to "M1", next the "M2", etc
  1. Wire the all of the pots to the analog pins 0 through 3
  1. Wire the five buttons with the correct resistors to pins digital pins 22-26