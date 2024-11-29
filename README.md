# Project: The Interplay of Linguistic Clarity and Surprisal: A study of the relationship between word duration and surprisal
The study uses a dataset of recorded and processed sentences, with surprisal values computed from a bigram language model, and phonetic durations analyzed with the MAUS and Praat speech processing tools.

**Key Findings**
Words with higher surprisal values tend to have longer durations. Shorter word durations dominate the dataset.

**Files in the Project**
sentence*.txt: Test sentences 1-10 used for the study.
sentence*.csv: Duration data files 1-10 for each sentence obtained with MAUS.
data.csv: Dataset containing word durations and surprisal values.
dur_freq.csv: Dataset containing word durations and their frequencies.
histogram.png: Histogram showing word duration frequencies.
linear_model.png: Regression plot of word durations against surprisal.
get_durations.py: Python script for duration data retrieval.
get_histogram.py: Python script for duration data analysis and visualization.
get_surprisals.py: Python script for surprisal data retrieval.
get_linear_mode.py: Python script for surprisal data analysis and visualization.
