# data_science_interview

This project is aimed at analyzing a dataset of questions and answers in order to gain insights and information about the data. The dataset consists of various questions and their corresponding answers, along with the difficulty level of each question.

The first step is to clean the data, which involves removing any unnecessary or irrelevant information, such as HTML tags, and performing other text preprocessing techniques, such as removing stop words and tokenizing the text.

Next, some descriptive analysis is performed on the data. This includes visualizing the distribution of word counts in the answers, as well as the relationship between the length of questions and answers and the difficulty level of the question.

The project then applies topic modeling to identify the main topics that the questions and answers are discussing. The LDA (Latent Dirichlet Allocation) algorithm is used to identify these topics, and the resulting topics are visualized using pyLDAvis.

Finally, network analysis is used to identify the relationships between the questions and answers in the dataset. The questions and answers are treated as nodes in a graph, and the edges between them are weighted based on the difficulty level of the question. The resulting graph is visualized using the NetworkX library.


the data was scraped from [here](https://github.com/alexeygrigorev/data-science-interviews)


if you want to see the [topic modeling](https://rawcdn.githack.com/h9-tect/data_science_interview/53b71a88a53cecc074cf9e397ed1e6f5f21f0c79/lda_visualization.html#topic=0&lambda=1&term=)
