# Steps invloved in tuning PID parameters

1) First I and D paraeters were set to zeros and tuned P parameter. With this car started with good steering angle and slowly after some time car started oscillating left and right. The frequency slowly started increasing within short duration of time.
2) Started tuning D paramter with I still at zero. This damped the oscillation when increased. The combination of P and D value were slowly adjusted to take all turns with less oscillations. P was increased more to take sharp turns and D to keep check on oscillations.
3) A PD controller worked well. But a small value of I was introduced to correct the error values over long duration of time. A large value of I gave a bad start. so only a small value was set. 
