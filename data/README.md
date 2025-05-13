# Dataset Information

This document provides information about the datasets used in this project.

## E-commerce User Behavior Dataset

**Source**: [Kaggle - E-commerce behavior data from multi category store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)

**Description**: This dataset contains behavior data for 7 months (from October 2019 to April 2020) from a large multi-category online store. Each row represents an event (view, cart, purchase) performed by a specific user on a specific item at a specific time.

**File Structure**:
- event_time: Time when event happened (in UTC)
- event_type: Type of event (view, cart, purchase)
- product_id: Product ID
- category_id: Product category ID
- category_code: Product category (electronics, appliances, etc.)
- brand: Brand name
- price: Product price
- user_id: User ID
- user_session: User session ID

**Sampling Strategy**: For this project, we will use data from only 1 month or select 2-3 specific categories to keep the dataset manageable.

## Online Retail II Dataset

**Source**: [Kaggle - Online Retail II UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

**Description**: This is a transnational dataset containing all transactions occurring for a UK-based online retail between 01/12/2009 and 09/12/2011. The company sells unique all-occasion gift-ware, and many of its customers are wholesalers.

**File Structure**:
- Invoice: Invoice number
- StockCode: Product code
- Description: Product name
- Quantity: Quantities of each product per transaction
- InvoiceDate: Day and time when the transaction was generated
- Price: Product price per unit
- Customer ID: Customer number
- Country: Country where the customer resides

**Sampling Strategy**: Complete dataset is usable as it is relatively small.

## Customer Personality Analysis Dataset

**Source**: [Kaggle - Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

**Description**: This dataset is for customer personality analysis, providing insights about the customers' various attributes, behaviors, and responses to marketing campaigns.

**File Structure**:
- People attributes (demographics, education, marital status)
- Products purchased (wines, fruits, meat, fish, sweets)
- Promotion response
- Place of purchase (store, web, catalog)

**Sampling Strategy**: Complete dataset is usable as it is small.

## Combining Datasets

For certain analyses, we may combine information from multiple datasets. The approach for integration will be documented in the respective notebooks.

## Data Preprocessing Considerations

- Handling missing values
- Normalization and scaling
- Feature encoding
- Time-based feature engineering
- Outlier detection and treatment

This information will be updated as we progress through the data analysis process.
