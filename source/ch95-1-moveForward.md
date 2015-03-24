# Beginner - Move Forward

Create a new file:

* Select the **File** menu
* Select **New**
* Select **New File**

Name it **moveFoward1.c**

Delete everything in the file, and replace it with:

```c
#pragma config(StandardModel, "VEX IQ Clawbot")

task main()
{
  setMotorSpeed(leftMotor, 50);
  setMotorSpeed(rightMotor, 50);
  sleep(2000);
}
```

Press **F5** to compile and download to the robot so you can run this in Virtual Worlds.
