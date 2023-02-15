# ROBUSTA

Title Of The Project :- MASTER SLAVE COMMUNICATION

Brief Description :- The Master Bot will be operate by human beings at control room by using hand gestures. Here the joystick is ADXL335 will produce a positive or 
                     negarive serial value transmitted by the TX433 to the Master. And the Master received the signal through RX433. The serial value determines the
                     direction and speed of the Master. When Master finds the obstacle cut off the power supply to L298N and the slaves are triggered and the gate is
                     opened using a servo. One of the slave send the live video footage of everything and detect the objects. Another one detect the metal and send 
                     the live location to the control room.
                     
Hardware Software Used :- Microcontroller ( Arduino UNO , Arduino Nano , Node MCU , ESP32(Camera Module) , ESP32 ) 
                          Motor Driver ( L298N )
                          Motor ( DC Motor , Servo Motor )
                          Trans-Receiver (RX-TX 433 MHz)
                          Sensor ( ADXL335 , LM393 ) 
                          
                          
                          
Process Flow :- Attached the file of Process Flow of our prototype
[Master Slave Process Flow.docx](https://github.com/AvrajeetGhosh/ROBUSTA/files/10742213/Master.Slave.Process.Flow.docx)
