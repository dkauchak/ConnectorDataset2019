# ConnectorDataset2019
This is the connectors dataset from:

David Kauchak, Gondy Leroy, Menglu Pei, and Sonia Colina.  2019. Predicting Transition Words Between Sentence for English and Spanish Medical Text. AMIA, 2019.

See the paper for more details about how the data was collected.

There are three parts to the dataset:

- connector_words.*.txt contains the English/Spanish connector words, organized by category

- EnglishWiki directory: contains two files corresponding to the positive and negative files.  Each file is a tab delimited file.  The negative file contains the filename and a sentence pair where the second sentence should not start with a connector.  The positive file contains the filename, the type of connector, the connector word, and a sentence pair where the second sentence starts with the connector.

- SpanishWiki directory: same setup for the Spanish data
