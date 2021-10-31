# Public Opinion Analysis of Taiwan 2020 Triple Stimulus Voucher–a Case Study of Facebook News Datafrom Mainstream Media

To know about how ppl response to the policy of Triple Stimulus Voucher, we get interaction data from main media's Facebook fanpages. Several insights were found through the analysis.

## File Contents
- step1 is getting the post and ppl's comment and reactions(like, heart, angry...) from Facebook fanpages.  
- step2 is aggregating the raw texts into posts
- step3 apply word segmentation on the corpus(This is an important step fore NLP on Chinese text mining)
- Other notebooks are several analysis such as LDA, assoication rules, word cloud and sentiment analysis based on the feature extracted

## Requirements
- Python version: 3.8
- crawler: [chrome driver](https://chromedriver.chromium.org/)
- word segmentation model: [ckip](https://github.com/ckiplab/ckip-classic)
- modeling: see reuquirements.txt

## Study
For the study, see [HSU, YING-CHIEH, "Public Opinion Analysis of Taiwan 2020 Triple Stimulus Voucher–a Case Study of Facebook News Datafrom Mainstream Media"(2021)](https://hdl.handle.net/11296/ea768j)

Note: I'm not the author of this study. I conducted data ingestion and analysis only.
