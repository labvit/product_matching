# product_matching
search product name in db by name similarity
The main idea is split search query to below
Qwerty123 123x32 (12haha) ---> qwerty 123 123 x 123 ( 12 haha )
Cost of similarity is count of similar words devided by count of all words
