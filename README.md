# Digital-Control-Pump-PLC
 We are going to be maintaining the pressure in a receiver on a compressor application.  There are 
two pressure switches which close at 90 and 110psi (low and high).  To control the pressure, we have 
one pump.  Additionally, we want to illuminate an indicator light when the pressure is above 90psi.
## IO / ASSIGNED MEMORY
I:0/0 ‐ Low pressure switch (closes at 90psi and above) 
I:0/1 ‐ High pressure switch (closes at 110psi and above) 
O:0/0 – Pressure pump 
O:0/1 – Pressure indicator light.
