# Bussiness_Meeting_Summarization_using_NLP_
Ever got stuck in a situation, where everyone wants to see a summary not full reports. Well, I face it during my school and college days where we spend a lot of time preparing a whole report but the teacher only has time to read the summary. Summarization has risen as an inexorably helpful way to tackle the issue of data over-burden. Extracting information from conversations can be of very good commercial and educational value. This can be done by feature capture of the statistical, linguistic, and sentimental aspects with the dialogue structure of the conversation. Manually changing the report to a summed up form is too time taking, isn’t that so? But one can rely on Natural Language Processing (NLP) techniques to achieve that. Text summarization using deep learning can understand the context of the entire text. Isn’t it a dream come true for all of us who need to come up with a quick summary of a document !!
Impact
Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting.
In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.

How text summarization works
In general there are two types of summarization, abstractive and extractive summarization.
Abstractive Summarization:
Abstractive methods select words based on semantic understanding, even those words did not appear in the source documents. It aims at producing important material in a new way. They interpret and examine the text using advanced natural language techniques in order to generate a new shorter text that conveys the most critical information from the original text.
It can be correlated to the way human reads a text article or blog post and then summarizes in their own word.
Input document → understand context → semantics → create own summary.
2. Extractive Summarization: 
Extractive methods attempt to summarize articles by selecting a subset of words that retain the most important points.
This approach weights the important part of sentences and uses the same to form the summary. Different algorithm and techniques are used to define weights for the sentences and further rank them based on importance and similarity among each other.
Input document → sentences similarity → weight sentences → select sentences with higher rank.
The limited study is available for abstractive summarization as it requires a deeper understanding of the text as compared to the extractive approach.
Purely extractive summaries often times give better results compared to automatic abstractive summaries. This is because of the fact that abstractive summarization methods cope with problems such as semantic representation,inference and natural language generation which is relatively harder than data-driven approaches such as sentence extraction.
