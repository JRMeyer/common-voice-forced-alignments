# Forced Alignments for Common Voice

The alignments in this repository were created using the Montreal Forced aligner. All languages went through the same aligments process, without a pre-trained model. Data for each language was trained separately.

The alignments are not guaranteed to be perfect, and there will likely be a correlation between amount of data and goodness of alignments, where more data yields better alignments. In the case the Montreal Forced Aligner could not find an alignment for a certain <audio,transcript> pair, it will be noted in the file `unaligned.txt`.

The TextGrids are readable by Praat.

To download the corresponding audio, go to the [[Common Voice download page]](https://commonvoice.mozilla.org/en/datasets).
