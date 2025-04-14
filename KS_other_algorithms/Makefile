CXXFLAGS += -std=c++11

sa: sa.cpp
	$(CXX) sa.cpp -o sa -O3 $(CXXFLAGS)

sa-debug: sa.cpp
	$(CXX) sa.cpp -o sa-debug -fsanitize=address $(CXXFLAGS)

clean:
	rm -f sa sa-debug

.PHONY: clean