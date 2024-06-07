# tr_emotbias_dataset
Annotated Turkish corpus of null subject sentences conveying emotions, each of them also given together with their original broader context in an additional separate column.
Originally created to evaluate gender stereotype of MT models when translating emotional expression. 
Dataset contains 1,734 sentences explicitly conveying six basic emotions as anger, pride, fear, sadness, shame, and joy. 
Approximately 300 sentences per emotion category, half of which are carefully chosen among the ones holding a covert feminine subject while the other half a covert masculine subject in the broader context which they were extracted from. 
Each sentence was manually annotated with its gold pronoun -he or she- as well as the distance between the contextual information and the phrases that convey the emotion. 

Data was extracted from two parallel corpora: 

1- OpenSubtitles that 2011 consists of 166,085,459 tokens. It is a sub-corpus of the Open Parallel Corpus (OPUS) - Turkish with 207,223,730 tokens and 31,148,523 sentences in total 

2- OpenSubtitles 2018 parallel – Turkish contains 630,921,773 tokens and 114,126,315 sentences in total 
