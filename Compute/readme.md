# Details of each python file: (alphabetically)

| File              | Function          | Description                                   |
|-------------------|---------------    |--------------------------------------------   |
| calc_config.py    | Config of calc    | Setting up of what kind of calculation to do  |
| compute.py        | execution         | Run the VQE code                              |
| estimators.py     | QC simulators	| A list of QC simulators to be chosen from	| 
| np_hartreefock.py | HF init state     | Custom Hartree Fock state                     |
| obs.py	    | Observable Definition | Where Hamiltonian is defined, mapped into Pauli Strings |
| ucc_trott.py      | Custom Ansatz     | Ansatz that allows Different ordering of Trotter decomposition |
| utils.py          | Helper functions  | -                                             |
| vqe.py            | VQE setup         | Modification of VQE will be done here         |

| Directory	    | Descriptions | 
| - 		    | - 	   |
| FakeBackends	    | Where FakeJohors of different specifications e defined. (modifications from FakeGuadalupe) |