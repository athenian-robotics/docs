# Background of Control Theory

When controlling motors, we're only able to send a signal in terms of a voltage. In practice, this is unwieldly and inefficient. Instead of calculating the voltage needed to achieve a certain task, we utilize control theory. Essentially, we give the motor a setpoint(a state that it would like to achieve). By using the motor encoder to find where the motor actually is, the motor can subtract where it is from where it would like to be to achieve its error. By analyzing properties of that error, as well as some constants introduced by the programmer, the motor applies the necessary voltage to reach its setpoint. By changing certain constants, we can alter the path that it takes to get to that setpoint.

# Feedforward and Feedback Control