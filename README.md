## Lattice Format
Main file is Cooling_Lattice_Benchmark.ipynb for creation and benchmark of lattice format.
Lattice file created at benchmarking.json
Beam input is 050625BeamInput_10000_4.04124T
Generated input g4bl file is G4BL_benchmark.g4bl
G4BL output files are Benchmark_g4bl_fieldmap.txt and 291025_benchmark_1000.txt
#### Data Formats
Initialising a json format of the following structure:


#### Units
All inputs and outputs must define their units with them. Standard set of units is below

Energy:	MeV \
Time:	ns \
Distance:	mm \
Field:	T \
Angles:	rad \
Frequency: MHz \
Density: g/cm3 \
Current: A/mm2 \
Beam format: Px and Py, not x', y' \
RF Phase: 0 degrees bunching, 90 degrees on-crest \
Coordinates: Cartesian
