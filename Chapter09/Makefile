
CXXFLAGS = -std=c++1z -Wall 

SOURCES=$(wildcard *.cpp)
BINARIES=$(patsubst %.cpp,bin/%,$(SOURCES))

default: $(BINARIES)

bin/%: %.cpp
	$(CXX) $(CXXFLAGS)  -o $@ $<  $(LDFLAGS)

clean:
	rm -f $(BINARIES)
