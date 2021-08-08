# EMDrama-Ubiq

This repository contains the Ubiquity/Docuscope output from tagging the
Early Modern Drama Corpus. It contains the tag files for the 1292 works
as well as the overall output files. See the
[README for the corpus](https://github.com/uwgraphics/EMDrama) for
more information.

This repository is mainly for internal use and is accessed by the
[Metadata Builder](https://uwgraphics.github.io/MetadataBuilder/).

These files were generated:

- From the files available
  [in the EMDrama SimpleText repository](https://github.com/uwgraphics/EMDrama)
- Using the command line version of Ubiquity available at
  [https://github.com/uwgraphics/Ubiqu-Ity](https://github.com/uwgraphics/Ubiqu-Ity)
- Using the Docuscope Dictionaries available at
  [https://github.com/docuscope/DocuScope-Dictionary-June-26-2012](https://github.com/docuscope/DocuScope-Dictionary-June-26-2012)

What is here:

- The overall CSV file (one row per text) is `EMD-ubiq.csv`. This file was copied to the
  [Official Corpus Metadata Repository](https://github.com/uwgraphics/VEP-corpora)
- The `token_csv` directory has a tokens file per text. This file is used by the
  SlimTV text viewer.
- `ubiq-README.txt` is the README output from the Ubiquity run. Which is not very useful.
