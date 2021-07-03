Target=helloTest
all:
	g++ -std=c++0x ./cpp/*.cpp -o ${Target} -I ./include
	#  -L./curl_win32/lib/lib -lcurl -lEPD_API -lpthread \
	#  -I ./include

.PHONY:clean
clean:
	rm -rf ${Target}