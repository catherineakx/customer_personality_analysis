# Customer Segmentation & Personality Analysis

##### By: Catherine Ang

---

### Background
Customer Personality Analysis refers to a detailed analysis of a company’s ideal customers. It enables a business to better understand its customers and makes it easier for them to modify the line-up of products according to the specific needs, behaviours and concerns from different groups of customers. For instance, instead of spending money to market a new product to every customer in the company’s database, a company can analyze and identify the customer segment which is most likely to purchase the product, and craft up marketing campaigns that promote the product only to that particular segment.

Reference: [Customer Personality Analysis on Kaggle](https://www.kaggle.com/imakash3011/customer-personality-analysis)

---

### Problem Statement
SweetTreats is a grocery retailer with both online presence and physical stores, selling a variety of products from wine to fruits, meat, fish, sweets and gold. It requires all customers to create an account with the retailer, indicating demographic details such as year of birth, education level, marital status, etc. Purchase transactions (both online and physical) by customers are also recorded in their accounts. Occasionally, SweetTreats sends out marketing communications to selected customers, sharing with them new promotional deals that they can enjoy as members of the retailer. 

To improve revenue, SweetTreats aims to address the following issues: 
- Can the customers of the retailer be segmented into groups for more effective targeting through marketing campaigns? 
- What are some key characteristics of each customer segment? 

---

### Conclusion

By looking at the purchasing habits and personal traits, the key characteristics of each customer segment and the respective marketing campaigns that can be implemented include: 


- Cluster 0: 
    - Low income and low spending - likely to be quite frugal and cautious of their spending
    - React less positively to campaigns but snag up deals 
    - Has a mixture of family who have kids and no kids, and family size of 1 up to 6
    - **Proposal: Marketing campaigns need to feature special deals / promotions with great discounts on frequently purchased items, so that customers can attain large amount of savings; campaigns can be done in-store, need not be online**


- Cluster 1: 
    - Low-to-mid income but mid spending 
    - React less positively to campaigns but snag up deals 
    - Has a mixture of family who have kids and no kids, and family size of 1 up to 6
    - **Proposal: Marketing campaigns need to feature special deals / promotions with great discounts on frequently purchased items (especially basic necessities), so that customers can attain large amount of savings; campaigns can be done in-store, need not be online**


- Cluster 2: 
    - Low income and low spending - likely to be quite frugal and cautious of their spending
    - React less positively to campaigns but snag up deals 
    - May not have kids, and family size of 1 up to 4
    - **Proposal: Marketing campaigns need to feature special deals / promotions with great discounts on frequently purchased items (especially basic necessities), so that customers can attain large amount of savings; campaigns can be done in-store, need not be online**


- Cluster 3:
    - High income and high spending 
    - React positively to campaigns, but do not snag up deals
    - Most may have kids and family size of 2 up to 4
    - **Proposal: Marketing campaigns should feature unique items that are only available to the retailer + are on a higher price point, since this group of customers has a higher purchasing propensity which makes them more adventurous to purchase new items; campaigns should be done online first to garner interest**
    
    
- Cluster 4: 
    - Low-to-mid income and low-to-mid spending 
    - React less positively to campaigns but snag up deals 
    - May not have kids, and family size of 2 up to 4
    - **Proposal: Marketing campaigns need to feature special deals / promotions with great discounts on frequently purchased items (especially basic necessities), so that customers can attain large amount of savings; campaigns can be done in-store, need not be online**


- Cluster 5:
    - High income and mid-to-high spending 
    - React positively to campaigns, but do not snag up deals
    - Most may have kids and family size of 2, up to 4
    - **Proposal: Marketing campaigns should feature unique items that are only available to the retailer + are on a higher price point, since this group of customers has a higher purchasing propensity which makes them more adventurous to purchase new items; campaigns should be done online first to garner interest**
    
    
- Cluster 6:
    - Mid income and mid spending 
    - React less positively to campaigns; do not necessarily snag up deals
    - Most may not have kids and family size of 1 up to 2 
    - **Proposal: Marketing campaigns should feature unique items that are only available to the retailer + are on a mid-to-high price point, since this group of customers has a mid purchasing propensity and are likely more adventurous to purchase new items; campaigns can be done in-store, need not be online**    
    
    
- Cluster 7:
    - Mid income and mid spending 
    - React less positively to campaigns; do not necessarily snag up deals
    - Most may not have kids and family size of 1 up to 2 
    - **Proposal: Marketing campaigns should feature unique items that are only available to the retailer + are on a mid-to-high price point, since this group of customers has a mid purchasing propensity and are likely more adventurous to purchase new items; campaigns can be done in-store, need not be online** 


---

### Python Library Used
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn
* Datetime
* Statsmodel
* Yellowbrick