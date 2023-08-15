# Analysis of spike amino-acid mutations in new second-generation BA.2 variant

Small analysis by Jesse Bloom of spike mutations a new second-generation BA.2 variant with large number of mutations.

Some background on the small number of sequences for this variant can be found:

 - [the Pango GitHub issue](https://github.com/cov-lineages/pango-designation/issues/2183)

 - [another Pango GitHub issue](https://github.com/sars-cov-2-variants/lineage-proposals/issues/606)

 - [Shay Fleishon's Twitter post](https://twitter.com/shay_fleishon/status/1690684068642357248)

 - [Ryan Hisner's Twitter post](https://twitter.com/LongDesertTrain/status/1690989522035617792)

 - [Marc Johnson's Twitter post](https://twitter.com/SolidEvidence/status/1691070379584815104)

The sequences analyzed in this repo are the first three reported isolates:

  - `hCoV-19/Israel/ICH-741198454/2023|EPI_ISL_18096761|2023-07-31`
  - `hCoV-19/Denmark/DCGC-647646/2023|EPI_ISL_18097315|2023-07-31`
  - `hCoV-19/Denmark/DCGC-647676/2023|EPI_ISL_18097345|2023-07-24`

These sequences are downloaded in [./gisaid_seqs](gisaid_seqs), which is not tracked (see acknowledgments of submitters [here](https://epicov.org/epi3/epi_set/230814qu?main=true)).
Within that subdirectory, the file [./gisaid_seqs/gisaid_hcov-19_2023_08_14_18.csv](gisaid_seqs/gisaid_hcov-19_2023_08_14_18.csv) has the mutations in those sequences called using NextClade.

The file [pango-consensus-sequences_summary.json](pango-consensus-sequences_summary.json) has the clade founder sequences from Cornelius Roemer.

The Jupyter notebook [analyze_muts.ipynb](analyze_muts.ipynb) analyzes the spike amino-acid mutations in these sequences.

They are listed in the following files:

 - [spike_aa_muts_relative_to_BA.2.csv](spike_aa_muts_relative_to_BA.2.csv)
 - [spike_aa_muts_relative_to_XBB.1.5.csv](spike_aa_muts_relative_to_XBB.1.5.csv)
 - [spike_aa_muts_relative_to_Wuhan-Hu-1.csv](spike_aa_muts_relative_to_Wuhan-Hu-1.csv)
