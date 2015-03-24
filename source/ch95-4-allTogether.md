# Beginner - All Together Now

Create a new file:

* Select the **File** menu
* Select **New**
* Select **New File**

Name it **moveAround.c**

Delete everything in the file, and replace it with:

```c
#pragma config(StandardModel, "VEX IQ Clawbot")

task main()
{

  // move forward
  setMotorSpeed(leftMotor, 50);
  setMotorSpeed(rightMotor, 50);
  sleep(2000);

  // move backward
  setMotorSpeed(leftMotor, -50);
  setMotorSpeed(rightMotor, -50);
  sleep(2000);

  // spin around
  setMotorSpeed(leftMotor, -75);
  setMotorSpeed(rightMotor, 75);
  sleep(8000);
}
```

Press **F5** to compile and download to the robot so you can run this in Virtual Worlds.

## Investigations

What happens when you change the two **50**s in `//move forward` to **15**s?

What happens when you change the two **50**s in `//move forward` to **100**s?
