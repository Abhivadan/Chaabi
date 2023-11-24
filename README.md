# Chaabi
1. Run the first file chaabi1.ipnyb with GPU otherwise it will take a lot of time. This code will give embeddings_combined.npy file which is then uploaded to Qdrant vector DB.
2. In the file  response.ipynb the last line of code you can enter your query in query sentence, and the output will be contextual answers to that query.

This code uses bert-base-nli-mean-tokens based sentence transformer and T5  Text-to-Text Transfer Transformer LLM model for.

The response for a query sentence "healthy snacks" is:
ID: 15435, Response: fresho Signature Croissants, Bagels in Bakery, Cakes & Dairy is the perfect snack.
ID: 6748, Response: Winkies tea cakes & slice cakes in Bakery, Cakes and Dairy: traditional butter cake light and crumbly cake. light on fruit and candied peel-only currants, raisins, and cherries, a light cake that is ripe to the taste of the cake.
ID: 455, Response: 1401 and 1121 raw rice ensures great quality and taste. bb Royal Basmati rice is best suitable for daily dishes like dal chawal, khichdi and kheer.
ID: 12825, Response: it relishes in aroma, given that a high nutrition value to any one diet. it can be attributed to its low glycemic index which assists in the control of diabetes, obesity & cholesterol.
ID: 25484, Response: Appalam is made hygienically in customary method with home made taste.

