# EDA and Dashboard Project

# Project Overview
This project involves exploratory data analysis (EDA) and dashboard creation for a Gen AI company offering an enterprise GPT product. The goal is to derive actionable business insights from the provided dataset, clean the data, and visualize key metrics using Power BI.

# Steps Undertaken

# **1) Data Analysis:**
- Performed EDA using Python (Pandas, Matplolib, etc.).
- Transformed the dataset and checked missing values.
- Summarized key statistics and trends.

# **2) Dashboard Creation:**
- Built an interactive dashboard in Power BI.
- Included visualizations like average Query Length, Response Time, and User Rating.

![Overview Dashboard GPT Usage Analysis](https://github.com/user-attachments/assets/b12c026f-e9b0-4810-a616-e14b71790bdf)



# **3) Business Insights:**

Based on the analysis of the Gen AI enterprise GPT product usage dataset, we identified the following key insights and recommendations:

1. **Query Length Variations**

![Query Length Variations](https://github.com/user-attachments/assets/78dd6ba9-2f34-409f-b862-a1b4336b4f6f)

   - **Insight**: Average query length is 55 characters, with significant variations.  
   - **Recommendation**: Implement autofill or suggestion features for enterprise users to streamline query submissions.


2. **High Response Times for Enterprise Users**

   ![High Response Time for Specific Users](https://github.com/user-attachments/assets/8a6eb8bf-2cbf-437d-b427-36d65dec158b)

   - **Insight**: Some enterprise users experience higher-than-average response times (2 seconds).  
   - **Recommendation**: Optimize query processing for enterprise users by allocating more server resources.

3. **Error and Feedback Patterns**
![Error Patterns Across Industries](https://github.com/user-attachments/assets/c9d91397-b7c1-4bde-8813-58bd4a222824)

   
   - **Insight**: Errors are common in the healthcare sector, while feedback is more frequent from education users.  
   - **Recommendation**: Address errors in healthcare and leverage education feedback to improve the product's user-friendliness.


# Repository Contents
- `Enterprise_GPT_Product_Usage_Dataset.csv`: The dataset used for analysis.  
- `EDA_analysis.ipynb`: Jupyter Notebook containing the code for data analysis and cleaning.  
- `PowerBI_Dashboard/`: Contains the Power BI dashboard `.pbix` file.  
- `Screenshots/`: Contains screenshots of the dashboard visualizations.


