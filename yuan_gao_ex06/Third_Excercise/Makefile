
GF=gfortran
O3FLAGS=  -O3
O0FLAGS=  -O0

all: O3 O0

O0: 
	$(GF) $(O0FLAGS)  a0.f90  -o a0_O0 
	$(GF) $(O0FLAGS)  a0_modified.f90  -o a0_modified_O0 
	$(GF) $(O0FLAGS)  b0.f90  -o b0_O0 
	$(GF) $(O0FLAGS)  b0_modified.f90  -o b0_modified_O0 
	$(GF) $(O0FLAGS)  c0.f90  -o c0_O0 
	$(GF) $(O0FLAGS)  c0_modified.f90  -o c0_modified_O0 
	$(GF) $(O0FLAGS)  d0.f90  -o d0_O0 
	$(GF) $(O0FLAGS)  d0_modified.f90  -o d0_modified_O0
	$(GF) $(O0FLAGS)  e0.f90  -o e0_O0
	$(GF) $(O0FLAGS)  e0_modified.f90  -o e0_modified_O0
	$(GF) $(O0FLAGS)  f0.f90  -o f0_O0 
	$(GF) $(O0FLAGS)  f0_modified.f90  -o f0_modified_O0 


O3:
	$(GF) $(O3FLAGS) a0.f90  -o a0_O3
	$(GF) $(O3FLAGS) a0_modified.f90 -o a0_modified_O3
	$(GF) $(O3FLAGS) b0.f90  -o b0_O3
	$(GF) $(O3FLAGS) b0_modified.f90  -o b0_modified_O3
	$(GF) $(O3FLAGS) c0.f90  -o c0_O3
	$(GF) $(O3FLAGS) c0_modified.f90  -o c0_modified_O3
	$(GF) $(O3FLAGS) d0.f90  -o d0_O3
	$(GF) $(O3FLAGS) d0_modified.f90  -o d0_modified_O3
	$(GF) $(O3FLAGS) e0.f90  -o e0_O3
	$(GF) $(O3FLAGS) e0_modified.f90  -o e0_modified_O3
	$(GF) $(O3FLAGS) f0.f90  -o f0_O3
	$(GF) $(O3FLAGS) f0_modified.f90  -o f0_modified_O3

clean:
	rm -rf *_O3 *_O0
