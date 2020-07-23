#How Facebook can save meaningful conversation

Any medium have one clear objective that it must support effective and meaningful conversation. Social media is not exception for it. But recently social media is imfamous for chaos instead of communication. In my personal opinion most of time trolling leads to this chaos.

Advancement in NLP and machine learning enhance ablities of machine to understand human languages with it's nuances.

There are multiple ways we can use to identify/classify troll comments on any random post. Following code will show simple way to implement troll classifier. With help of it we can define importance of comments according to it's meaning and sort comments order in such a way that more meaningful comments get more visibility.

Instead of creating classifier from scratch, we can make use of transfer learning. By defination storing knowledge gaining while solving one problem and applying it one different but related problem is known as transfer learning.

For language understanding we are using BERT. BERT is pre-trained contextual language representation developed by Google. Hence instead of start with dataset generation to model generation/validation we directly use language model to understand nuance and identify trolling.
