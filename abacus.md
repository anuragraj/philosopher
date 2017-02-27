Aggregate data from multiple experiments and adjusts label-free quantification to accurately account for peptides shared across multiple proteins


## Usage

`philosopher abacus [flags] [folders]`


## flags

`--comb`

a pre-formed combined protXML file

`--pepProb`

minimun peptide probability (default "0.5")

`--prtProb`

minimun protein probability (default "0.9")


## Example

Aggregating data from 3 different experiments, in 3 different workspaces

`philosopher abacus control/ treatment_1/ treatment_2/`

Aggregating data from 3 different experiments, in 3 different workspaces and using a pre-existing protXML combined file.

`philosopher abacus --comb combined.potxml control/ treatment_1/ treatment_2/`


## FAQ

_What exactly do I need to do before running Abacus ?_

You need to work on each individual experiment workspace before running Abacus. Each folder containing individual experimental data must be converted to a Workspace and must have its data analyzed by the filter command.

_I don't have a combined protXML file, how do I get one?_

Philosopher will create one for you

_Where should I execute the abacus command ?_

The command should be execute one level above the experimental data
