This directory contains all experimental data used in ``Funtional network inference of the suprachiasmatic nucleus'' by J.H. Abel et al.



- One folder contains trajectories and location coordinates for cells which could be continuously tracked throughout all conditions (full_time_trajectories)
- One folder contains trajectories, location coordinates for all cells which could be tracked during the TTX washout time period (ttx_wash_trajectories)
- raw_mic_scores contains pairwise MIC scores for cells within each SCN. The MIC of a pair of cells cell1,cell2 is found in the matrix at (cell1, cell2) (or equivalently (cell2,cell1) since MIC is symmetric)

Within these files, each cell is in a column, with each 1h sample as an entry within that column. Locations match cells. MIC scores are presented as an adjacency matrix.

For the full trajectories of SCNs 1-5:
    ttx_time = [90,109,82,107,113]
    wash_time = [234,252,224,240,242]

Jan. 30, 2016




We have added the raw pairwise MIC scores for each SCN. To get the network associated with each SCN, apply thresholds = [0.949,0.935,0.9895,0.968,0.969].

May 16, 2016


For additional questions or the code used in processing this data, please contact the authors.
