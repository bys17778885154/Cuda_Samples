APPS=hello

all: ${APPS}

%: %.cu
	nvcc -O2 -o $@ $<
clean:
	rm -f ${APPS}
