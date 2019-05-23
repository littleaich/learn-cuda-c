APPS=hello

all: ${APPS}

%: %.cu
	nvcc -O2 -arch=sm_50 -o $@ $<
#	nvcc -O2 -o $@ $<
clean:
	rm -f ${APPS}
