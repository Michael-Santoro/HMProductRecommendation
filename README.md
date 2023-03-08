# HMProductRecommendation

In retail, customer product recommendations can be invaluable to the customer experience. The H&M Group is a family of brands and businesses with 53 online markets and approximately 4,850 stores. The online store offers shoppers an extensive selection of products to browse through. However, with too many choices, customers might need help finding what interests them or what they are looking for, and ultimately, they might not make a purchase. 
Customers are creatures of habit, and making good product recommendations to repeat customers is possible based on their transaction history. The question is how to handle new customers. This experiment outlined in this paper offers a proposed method for providing new customers with product recommendations without prior knowledge of their purchasing habits.

There are a couple of assumptions this proposed solution takes:
-	Someone can sort products into groups based on visual features.
-	Grouped product relationships in purchases will be similar across products within groups. In other words, when customer A adds an item from group 1 to their cart, then adds an item from group 2 to their cart, there is a chance that customer B will take the same action.

Class labels can be somewhat simplistic; the experimentation will provide an example. Instead of class labels, the grouping will be done on imagery using principals from the Artificial Intelligence (AI) Natural Language Processing (NLP) community. The AI NLP community has recently made fantastic advances in applications, including text generation, summarization, image generation, chatbots, coding, and language translation applications. The great thing about these problems is that they can understand the context and semantics like humans. The plan is to use the same semantic understanding applied in natural language processing applications such as text summarization to images to a more exacting grouping of products. The goal is that the image decomposition method may have more context than a human-applied word.

Once the images have been grouped into structures based on their distance proximity, a probabilistic analysis will be done on the resulting basket purchases.
