CC = nvcc
CFLAGS = -I.
DEPS = main.cpp
OBJ = main.o

%.o: %.cpp $(DEPS)
    $(CC) -c -o $@ $< $(CFLAGS)

project_executable: $(OBJ)
    $(CC) -o $@ $^ $(CFLAGS)

clean:
    rm -f *.o project_executable
