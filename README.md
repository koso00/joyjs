# Joyjs

A slim and customizable js virtual joystick.
(It requires jQuery)

## How to

``` javascript

joystick = new joystick("#target");
joystick.start()

```

## APIs

``` javascript

joystick.start()

```

Start the joystick handler

``` javascript

joystick.pause()

```

Pause the joystick handler

``` javascript

joystick.deg()

```

It returns the angle of the joystick

``` javascript

joystick.deltaX()
joystick.deltaY()

```

Returns deltaX or deltaY of the stick

``` javascript

joystick.distance()

```

Returns the distance of the stick