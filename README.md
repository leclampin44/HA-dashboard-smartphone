# Home Assistant dashboard with an old smartphone

I'm having some old smartphones that stay in my drawer for a long time

I have used on of them as a little dashboard for Home Assistant in my house and it works pretty well, I wanted to share this here


# Hardware

For this project we will use a old Motorola G4 plus, but it can be applied with any other old android smartphone. Having a facial camera is a plus though.

## Custom rom (optionnal)

## Root (optionnal)


# Kiosk mode

Now we will use "Fully" android application to set the smartphone as 

## "Fully" configuration


## Lockscreen rotation

Even with all the options sets in Fully, we still have to deal with the quick rotation we have when the phone is detecting a motion.

This 1 sec rotation is due to the lockscreen rotation that is still in portrait even after setting all the environement to landscape.

To change this, we will need root access to the phone, and edit the follwing file : /system/build.prop

And add the following line : 

```
lockscreen.rot_override=true
```

And reboot the phone
