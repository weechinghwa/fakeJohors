# fakeJohors: Quantum Computer requirements for nuclear structure (pairing correlation) calculations.

## Setup
```sh
pip install requirement.txt
```

## Running the code
To run the code, execute the following command in the "/Compute" directory. 
```sh
python compute.py -i 2121_He6_herm_1 -s 100 -o SPSA -e no -n Hlp -esti esti0 -tc TerminateLnFit10stepRel_A08
```

## FakeJohor selections
Navigate to /Compute/estimators.py to see the list of available FakeJohors. Replace esti0 with the desired FakeJohor ID (e.g., esti_fj002) in the command above.
Example: 
```sh
python compute.py -i 2121_He6_herm_1 -s 100 -o SPSA -e no -n Hlp -esti esti_fj002 -tc TerminateLnFit10stepRel_A08
```

## Additional Information
For more details on the command-line arguments and their options, use the "--help" flag.
```sh
python compute.py --help
```