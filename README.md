# syntactic_complexity_in_LLMs
Datasets used in the manuscript: 'Tracing the complexity profiles of different linguistic phenomena through the intrinsic dimension of LLM representations' by M.Baroni, E.Cheng, I. De Dios Flores, F.Franzon available at [arxiv.org/abs/2601.03779](http://arxiv.org/abs/2601.03779).

The archive [datasets_syntactic_complexity.zip](https://github.com/franfranz/syntactic_complexity_in_LLMs/blob/main/datasets_syntactic_complexity.zip) contains all the .txt files with tab-delimited fields used for the experiments, as described below: 

## datasets
### coordination/subordination
*that_vs_and-c2.txt* - the subordination vs. coordination contrast, 2-clause pairs, with fields:
- subordinated
- coordinated

*that_vs_and-c3.txt* - the subordination vs. coordination contrast, 3-clause pairs, with fields:
- subordinated
- coordinated

*that_vs_and-c4.txt* - the subordination vs. coordination contrast, 4-clause pairs, with fields:
- subordinated
- coordinated


### center vs right embeddings

*center_right_clauses.txt* - the center-embedding vs. right-branching minimal pairs, with fields:
- center embedding
- right branching

### ambiguous vs unambiguous attachment

*ambiguity_dataset.txt* - the ambiguous vs. non-ambiguous triples, with fields:
- ambiguous attachment
- high attachment
- low attachment

**Please note that** the 'ambiguity_dataset.txt' was originally developed by I. De Dios Flores and [], and is conserved in [link]. Please refer to the original publication if you reuse it. 

