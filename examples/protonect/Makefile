all: Protonect decode decode2
    

Protonect: Protonect.h Protonect.cpp
	g++ -Wall -I ../../libusb/include/libusb-1.0/  -L ../../libusb/lib/ -o Protonect Protonect.cpp  -lusb-1.0 -lboost_thread

decode: decode.cpp
	g++ -Wall -o decode decode.cpp  -lopencv_core -lopencv_highgui
	
decode2: decode2.cpp
	g++ -Wall -o decode2 decode2.cpp  -lopencv_core -lopencv_highgui
