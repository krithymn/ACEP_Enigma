- Hi, WE're ACEP Enigma team
- This is a sample of the program that we used to detect and aboid the object.
- Example:
- 1. Receives a positive speed value. Then multiply it by -1 making robot to move forward.
- 2. Receives the gyro value to calculate the degree of the motor whether it's left or right using the PD Control formula.
- 3. The turning of the front wheel came from the maximum value. 
- 4. The turning of the front wheel come from the minimum value also.
- 5. Take the result value, multiply it with -1 to control the front wheel. If the robot is tilted to the left, the wheels must turn to the right. If the robot is tilted to the right, the wheels must turn to the left. So if we don't converted the value the robot won't turn to the opposite direction when it tilted to another direction.
- 6. Take the degree value of the motor to compare with the result value. If it greater than the calculated value, the motor C will reverse. 
- 7. If the first condition is false, the second condition will be checked whether the motor degree is less than the calculated value. If yes, then let the motor C go forward.


<!---
krithymn/krithymn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
