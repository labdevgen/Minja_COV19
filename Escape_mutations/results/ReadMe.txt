Data from human_sera_raw_data.txt (see data folder for desciption).
Pipeline:
1. Filter q-th percentile of mutations escape score
2. Overlap between samples (humans)

Results:
Files .csv - list of mutations, N_samples indicates in how many samples the mutation appeared in q-th percentile (23 max)
Files .png - hist of N_samples distribution for observed data and randomized control (shuffled percentile values)