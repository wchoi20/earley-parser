# earley-parser
Assignment for NLP course at JHU (CS 601.465)

The goal of the assignment was to create an Earley parser using the Earley recognizer provided as a starter file.

Brief description of the files is the following:

  papa.gr: a small grammar file generated from a simple sentence "Papa ate the caviar with a spoon"
  papa.sen: some sample sentences using only vocabs from papa.gr
  parse.py: an initial Earley parser
  parse2.py: an improved Earley parser using batch duplicate check and vocabulary specialization
  recognize.py: the Earley recognizer provided as a starter file
  wallstreet.gr: a large grammar file generated from wallstreet corpus
  wallstreet.sen: some sample sentences using only vocabs from wallstreet.gr
  wallstreet1.sen: two sentences from wallstreet.sen for faster test runs
  
  where .gr represents grammar files and .sen represents sentence files.

To run the recognizer,

  ./recognize.py [.gr file] [.sen file]

To run the parser,

  ./{parse.py | parse2.py} [.gr file] [.sen file]

An example run for the parser would be the following:

  ./parse.py papa.gr papa.sen
