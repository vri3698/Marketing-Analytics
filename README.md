## ** Overview:**

*Technical Domain:* Text Analysis + Customer Analytics

*Data Source:* Tablet review data (product_reviews.csv)

### **Part 1: Text Analysis**
1. **Sentiment Analysis:**
   - Applied Natural Language Processing techniques to calculate sentiment polarities (positive, neutral, negative) for Kindle attributes: screen, customer service, weight, price.
   - Ratio of positive to negative reviews determined for each attribute using pandas' value_counts.

2. **Topic Modeling (Latent Dirichlet Allocation):**
   - Employed Latent Dirichlet Allocation on Amazon Kindle reviews after cleaning and removing stop words.
   - Generated models for 3, 5, and 7 topics, naming topics based on top ten words.
   - Assessed topic overlap and calculated perplexity for each model.

### **Part 2: Customer Analytics**
1. **Customer Lifetime Value (CLV) Analysis:**
   - Calculated baseline CLV for Parimus Financial Services (PFS) customers.
   - Evaluated two strategic options: increasing retention rate and changing customer mix.
   - Computed the maximum amount of one-time expenditure PFS should be willing to spend for each option, considering a 10% discount rate.

2. **Choice Model and Elasticities:**
   - Developed utility equations for three brands (B1, B2, B3) considering price attributes and demographics.
   - Identified coefficients with meaningful differences across equations.
   - Calculated and interpreted own and cross-price elasticities based on a multinomial model.

### **Key Technical Learnings:**
- Text preprocessing for sentiment analysis: cleaning, removing stop words, and stemming.
- Application of Latent Dirichlet Allocation for topic modeling.
- Customer Lifetime Value calculations and strategic decision-making.
- Utility equation formulation for choice modeling.
- Elasticity calculations and interpretation in a choice model context.

### **Technical Tools:**
- Python for sentiment analysis and topic modeling (using pandas, nltk, sklearn).
- Analytics and statistical methods for CLV and choice modeling.
- Documentation using LaTeX.

**Note:** Results may vary based on text preprocessing and modeling parameters chosen.
