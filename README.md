# MetamaisKauli-
Spele
import random
while true:
    metiens = random.randint(1, 6)
    print ("Tu uzmeti:", metiens)

    if metiens >= 4 :
        print ("Tu uzvareji!")
    else:
        print ("Tu zaudēji.")

    atbilde = input ("Vai tu gribi spēlēt vēlreiz? (j/n): ")
    if atbilde.lower  () != "j":
        break
