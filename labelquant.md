Protein quantification based on isotope labeling


## Usage

`philosopher labelquant [flags]`


## Flags

`--brand`

type of label (tmt or itraq)

`--dir`

Folder path containing the raw files

`--ext`

Spectra file extension (mzML, mzXML)

`--normToChannel`

normalize intensities to a control channel (provide a channel number as control)

`--normToIntensity`

normalize intensities to the total intensity from all channels

`--plex`

number of channels

`--tol`

M/Z tolerance in PPM (default "10")


## Example

A 10-plex TMT analysis using channel 4 as normalization reference

`philosopher freequant --brand tmt --plex 10 --dir mz/ --ext mzXML --normToChannel 4`
