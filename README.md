# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.

## APPARATUS REQUIRED

Trainer Kit, DSO(10MHz), Patch Cords and Power Supply (0-30V)

## PROCEDURE

## 1.Natural Sampling
1. Switch on the DCL-10 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT of buffer to IN of Flat Top Sampling block.
4. Set clock to Internal mode (INT clk) using switch Sw4..
5. Set sampling frequency to 8kHz using switch $1.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.

## 2. Sample and Hold
1. Switch on the DCL-01 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT to IN of Sample and Hold block.
4. Set clock to Internal mode (INT clk) using switch Sw4.
5. Set sampling frequency to 8kHz using switch S1.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Sample and Hold block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.

## 3. Flat Top Sampling
1. Switch on the DCL-01 kit with correct power supply polarity.
2. Connect 1kHz, 5Vpp sine wave output to BUF IN of buffer.
3. Connect BUF OUT to IN of Flat Top Sampling block.
4. Set clock to Internal mode (INT clk) using switch Sw4.
5. Set sampling frequency to 8kHz using switch 51.
6. Set 50% duty cycle using switch Sw2.
7. Connect OUT of Flat Top Sampling block to IN1 of 2nd order Butterworth Low Pass Filter.
8. Observe output and repeat steps for 2kHz sine wave input.

## CIRCUIT DIAGRAM

## NATURAL SAMPLING
![image](https://github.com/user-attachments/assets/393e4620-467e-4528-80a3-e0dad1d298cc)
## SAMPLE AND HOLD
![image](https://github.com/user-attachments/assets/868fbedd-e7bd-4b33-84c0-8e013626cbe3)



## MODEL GRAPH
## NATURAL SAMPLING
![image](https://github.com/user-attachments/assets/be6c0c93-7df6-42ed-8b6b-5e5247482cc0)

## SAMPLE AND HOLD
![image](https://github.com/user-attachments/assets/cdc71feb-9eb3-44f9-8a85-4785dd513294)


## TABLE
![image](https://github.com/user-attachments/assets/e3b6afa9-c6c7-40f8-ad16-ecdae217fd43)

## OUTPUT GRAPHS
![image](https://github.com/user-attachments/assets/f1b5502a-cd49-4628-8ba9-eb30eaf15d15)
![image](https://github.com/user-attachments/assets/a5e9be47-7470-4029-ab6e-da829ae33b79)



## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
