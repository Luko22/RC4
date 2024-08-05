# RC4
 RC Car Control central (RC4)

After quickly realizing Arduino’s limitations, I naturally gravitated towards esp32 boards. The way was long (for my wallet) and many battles were lost (the Legens of the ESP32s  vs 9v battery), but alas I had what I needed for a remote controlled car project. I’ve always loved rc cars, but why buy them, when I could just make am customizable upgradeable one. However, this is always easier said than done.
Technologies and tools used
2-wheel robot car kit, RFnano/ESP32, esp32cam, DC motor driver, 3s LiPo battery, OpenCV, Arduino IDE… 
## Procedure
-	Assembled the car kit
-	Attached motor driver and jump wire connections to driver and board
-	Made remote circuit, tested fine-tuned to ensure fluent communication with the two boards
-	Added ESP32 cam and ran basic webserver stream
-	Made html page with the camera feed and commands
## Challenges & solutions 
-	burnt my previous pair of esp32 boards I was using for testing with a 9V battery- got new ones, or used boards with higher capacity voltage regulators
	
## Further applications
-	Toy rc car- just would have to make a 3d body for it 
-	Automation- with OpenCV and similar algorithms
