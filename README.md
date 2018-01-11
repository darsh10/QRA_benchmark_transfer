
# format of a data
# each directory MUST contain the following
# corpus.tsv.gz a TAB separated file of question_id,title,target corpus.tsv which is gziped
# train.pos.txt a training file of question_id1,question_id2 space separated of similar questions
# train.neg.txt a training file of question_id1,question_id2 space separated of unsimilar questions
# dev.pos.txt, dev.neg.txt, test.pos.txt, test.neg.txt in a similar way
# For source file : We will need atleast corpus.tsv.gz, train.pos.txt and train.neg.txt
# For target file : We will need atleast corpus.tsv.gz, dev.pos.txt, dev.neg.txt, test.pos.txt and test.neg.txt

Datasets:

1) AskUbuntu/Android/Apple/SuperUser
This repo contains a preprocessed collection of questions from the AskUbuntu/Android/Apple/SuperUser forum of the StackExchange family.

corpus.tsv.gz contains the question title and body for each question.

dev.[pos|neg].txt and test.[pos|neg].txt are the development and test dataset containing positive and negative instances respectively.

train.[pos|neg].txt are the training dataset containing positive and negative instances respectively

2) Quora

Crawled from the homonymous website http://qim.ec.quoracdn.net/quora_duplicate_questions.tsv

Same format as above

3) Sprint FAQ

Newly crawled from the homonymous website https://support.sprint.com/support/device/Sprint/Sprint_LiveProtrade-dvc8240001prd?intent=faq

Same format as above
