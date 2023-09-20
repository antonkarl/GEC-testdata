# GEC-testdata
Grammatical Error Correction for Icelandic - Test Data

The repository consists of data for evaluating an Icelandic spell and grammar checker. The data consists of three files for each testing element, with a reference to where the text was taken from:

- IGC_001_original.txt
* IGC_001_corrected.jsonl
+ IGC_001_metadata.txt

The above example consists of text from the Icelandic Gigaword Corpus (IGC), the first text in the test set. The format of the 'corrected' file depends on the test data's type, of which there are three:

1. Errors are marked, but not corrected or labeled further. The 'corrected' file is a .jsonl file.
2. The text as a whole ic corrected, with no span marking or further labeling. The 'corrected' file is a .txt file.
3. Errors are marked, corrected and each correction is supported with arguments. The arguments consist of a few sentences, e.g. with reference to published rules on Icelandic spelling and grammar. The 'corrected' file is a .txt file. 
