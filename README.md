# PhD-Data
Files relating to my PhD thesis.
'Alchemy/BabelNet Movie/Music Similarity Scores' files provide the between-category and within-category scores for every category. For example, the line 'Action-Action: 0.012553' in 'Alchemy Movie Similarity Scores.txt' means that, when using AlchemyAPI, the Action genre has a within-category similarity of 0.012553. The line 'Action-Film-Noir: 0.015349', from the same file, means that the between-similarity of Action and Film Noir is 0.015349.

'Alchemy/BabelNet Movie/Music genres with greater than or equal similarity' files contain categories that have higher between-category similarity than within-category similarity. For example, consider the following line from 'Alchemy Movie Genres with greater than or equal between similarity':

Action	['Film-Noir', 'Mystery', 'Thriller', 'Western'](4)

This line says that 4 genres have a higher between-category similarity than the Action genre's within-category similarity. These genres are Film Noir, Mystery, Thriller and Western.
