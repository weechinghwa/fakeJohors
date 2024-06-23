"# vqe_pair" 

# Run the following lines (in vqe_run_command.sh) to run the code
python compute.py -i 2121_He6_herm_1 -s 100 -o SPSA -e no -n Hlp -esti esti0 -tc TerminateLnFit10stepRel_A08

# FakeJohor selections
Navigate to /Compute/estimators.py for the list of available FakeJohors (replace esti0 with the desired FakeJohor ID, e.g. esti_fj002 )