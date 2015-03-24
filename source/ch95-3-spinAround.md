# Beginner - Spin Around

Create a new file:

* Select the **File** menu
* Select **New**
* Select **New File**

Name it **spinAround.c**

Delete everything in the file, and replace it with:

```c
#pragma config(StandardModel, "VEX IQ Clawbot")

task main()
{
  setMotorSpeed(leftMotor, -75);
  setMotorSpeed(rightMotor, 75);
  sleep(8000);
}
```

Press **F5** to compile and download to the robot so you can run this in Virtual Worlds.
