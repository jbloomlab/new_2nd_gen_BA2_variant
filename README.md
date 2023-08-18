# Analysis of spike amino-acid mutations in BA.2.86 (a new second-generation BA.2 variant)

Small analysis by Jesse Bloom of spike mutations in BA.2.86, a new second-generation BA.2 variant with large number of mutations.

Some background on the small number of sequences for this variant can be found:

 - [the Pango GitHub issue](https://github.com/cov-lineages/pango-designation/issues/2183)

 - [another Pango GitHub issue](https://github.com/sars-cov-2-variants/lineage-proposals/issues/606)

 - [Shay Fleishon's Twitter post](https://twitter.com/shay_fleishon/status/1690684068642357248)

 - [Ryan Hisner's Twitter post](https://twitter.com/LongDesertTrain/status/1690989522035617792)

 - [Marc Johnson's Twitter post](https://twitter.com/SolidEvidence/status/1691070379584815104)

The sequences analyzed in this repo are the first four reported isolates:

  - `hCoV-19/Israel/ICH-741198454/2023|EPI_ISL_18096761|2023-07-31`
  - `hCoV-19/Denmark/DCGC-647646/2023|EPI_ISL_18097315|2023-07-31`
  - `hCoV-19/Denmark/DCGC-647676/2023|EPI_ISL_18097345|2023-07-24`
  - `hCoV-19/USA/MI-UM-10052670540/2023|EPI_ISL_18110065|2023-08-03`
  - `hCoV-19/England/GSTT-230817LSBC55/2023|EPI_ISL_18111770|2023-08-13`

These sequences are downloaded in [./gisaid_seqs](gisaid_seqs), which is not tracked (see acknowledgments of submitters [here](https://epicov.org/epi3/epi_set/230818zh)).
Within that subdirectory, the file [./gisaid_seqs/nextclade_muts.csv](gisaid_seqs/nextclade_muts.csv) has the mutations in those sequences called using NextClade.

The file [pango-consensus-sequences_summary.json](pango-consensus-sequences_summary.json) has the clade founder sequences from Cornelius Roemer.

The Jupyter notebook [analyze_muts.ipynb](analyze_muts.ipynb) analyzes the spike amino-acid mutations in these sequences.

They are listed in the following files:

 - [spike_aa_muts_relative_to_BA.2.csv](spike_aa_muts_relative_to_BA.2.csv)
 - [spike_aa_muts_relative_to_XBB.1.5.csv](spike_aa_muts_relative_to_XBB.1.5.csv)
 - [spike_aa_muts_relative_to_Wuhan-Hu-1.csv](spike_aa_muts_relative_to_Wuhan-Hu-1.csv)
