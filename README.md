# [Find Your Right Companies with SCREENER | the Data Library (Python)](https://developers.lseg.com/en/article-catalog/article/find-your-right-companies-with-screener-eikon-data-apis-python)
## Pre-requisites:
- LSEG Workspace application with an access for RD library desktop session, or RDP account for platform session
- Python 3.9 or above
- Python libraries
  - pandas==2.1.4
  - refinitiv-data==1.6.0

## Introduction
If you have a workflow which requires to search for companies that match your criteria. For example:
- "Companies that Market Cap is greater than 5,000M USD, in NYSE, in Energy business and 3 months return is more than 15%"
- "Companies that 3 months return is more than 15%, 52 weeks return is more than 10% and is in the Stock Exchange of Thailand"

**This article will guide you to the following topics:**
1. Use the SCREENER app to define a search syntax
2. Use LSEG's Refinitiv Data Library (Python) to retrieve companies list from the defined syntax.
3. Sample code and Jupyter notebook file is available in the top right panel of this article.

**SCREENER App on Workspace Desktop**
SCREENER, which can be used to screen public & private companies using a variety of criteria, is a flexible idea-generation tool that allows you to find securities in the investable universe that display certain characteristics and match your investment philosophy or style.
You can create simple and sophisticated filters and ranks on a broad range of factors to identify new investment opportunities.

## Reference
- (LSEG's Refinitiv Data Library for Python - Quick Start Guide)[https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-library-for-python/quick-start]
- (Example code: EX-1.01.08-Screeners.ipynb)[https://github.com/LSEG-API-Samples/Example.DataLibrary.Python/blob/main/Examples/1-Access/EX-1.01.08-Screeners.ipynb]
