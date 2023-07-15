# Mercari-E-commerce-Dataset

Welcome to the Mercari E-commerce Dataset Analysis repository! In this project, I explore a fascinating dataset from the Mercari e-commerce website to extract valuable insights about product listings. By conducting in-depth analyses and leveraging machine learning techniques, I uncover meaningful information that can guide improvements in item descriptions and enhance overall product listings.

Introduction
In the ever-expanding world of e-commerce, understanding underlying trends and patterns is crucial for success. In this blog post, I delve into a fascinating dataset from the Mercari e-commerce website, extracting valuable insights about product listings. By exploring various features, conducting in-depth analyses, and leveraging machine learning techniques, I uncover meaningful information that can guide improvements in item descriptions and enhance overall product listings.

Missing Values and Price Distribution
I begin our analysis by examining missing values in the dataset. Notably, I find that the "brand_name" feature has a 42% missing value rate, while the "category_name" feature has a 0.44% missing value rate. These missing values can provide valuable insights into consumer behavior and preferences, enabling sellers to better understand their target audience.

Next, I shift our attention to the price distribution. Through a histogram analysis, I observe a right-skewed pattern, indicating a higher frequency of products priced below 50 USD. To enhance visualization and facilitate further analysis, I apply a log transformation to the price feature. This transformation not only improves visualizations but also proves beneficial when building machine learning models, enabling more accurate predictions and insights.

Exploring Relationships
To gain a deeper understanding of the dataset, I explore the relationship between price and various factors. Firstly, I conduct an Analysis of Variance (ANOVA) to examine the impact of item condition on price. The results highlight that the condition of the product significantly affects its price. This finding emphasizes the importance of accurately representing the condition of products in listings, as it directly influences their perceived value.

I further investigate the relationship between price and shipping by conducting a T-test. The findings, at a 95% confidence interval, suggest that items shipped by the seller have a lower mean price compared to items shipped by the buyer. This information can help sellers make informed decisions regarding shipping options and pricing strategies, optimizing their listings for maximum profitability.

Unveiling Categories and Brands
Moving on, I delve into the category column, splitting it into three separate columns: main category, sub-category 1, and sub-category 2. An analysis is then performed on the 11 main categories present in the dataset. Through hypothesis testing, it was revealed that prices significantly vary across these main categories, providing sellers with valuable insights into market dynamics and pricing strategies. Understanding the pricing dynamics of different categories enables sellers to position their products competitively and make informed pricing decisions.

Within the dataset, the women's category stands out, encompassing approximately 600,000 products. The highest-selling products within this category are athletic apparel such as pants, tights, leggings, and makeup products, which explains why Beauty is the second-highest-count category. Understanding the popularity of specific categories allows sellers to prioritize their inventory and marketing efforts, ensuring they cater to the demands of their target audience effectively.

Analyzing Text Data and Topics
To uncover deeper insights, I analyze the text data in the dataset, specifically the item descriptions. Using the Natural Language Toolkit library (NLTK), I process the descriptions to reveal the relationship between price and description length. Surprisingly, I observe that the price does not significantly vary based on the length of the description. This finding empowers sellers to focus on crafting concise yet impactful descriptions without worrying about the direct impact on pricing.

Next, I apply the Latent Dirichlet Allocation algorithm to identify the major topics underlying the item descriptions. After selecting 11 major topics, I discover that certain topics hold significant weights for specific words. For example, "topic_0" is associated with words like "game," "months," and "wear." These hidden topics shed light on the nature of purchased products and can guide sellers in improving their item descriptions by incorporating relevant topic-specific words. By tailoring their descriptions to align with specific topics, sellers can appeal to the preferences of their target audience, ultimately boosting sales.

Conclusion
My exploration of the Mercari e-commerce dataset has unearthed valuable insights into product listings. From missing value analysis to price distribution, relationships between price and various factors, category and brand dynamics, and text data analysis, each aspect has contributed to a deeper understanding of the dataset. Armed with these insights, sellers can make informed decisions, revamp their item descriptions, and enhance the overall quality of their product listings. Stay tuned for more data-driven adventures in the world of e-commerce!

Thank you for visiting our repository. Feel free to explore the code and findings in detail.
