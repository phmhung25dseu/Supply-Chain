# Supply Chain 
<img width="1796" height="1003" alt="image" src="https://github.com/user-attachments/assets/529703f7-ab94-4886-874b-07089f3a8557" />
<details> 
<summary><strong>I. Introduction</strong></summary>

DataCo is a global company.  
The dataset details areas of impactive activities such as provisioning, production, sales and commercial distribution.  
Need to build a Supply Chain dashboard to identify patterns, trends, and insights that support decision-making and improve supply chain performance.

</details>

<details>
<summary><strong>II. Data Dictionary</strong></summary>

Dataset includes **53 columns** and **180,519 rows**.  
The table below describes the meaning of each column in both English and Vietnamese:

| Column                     | Explanation (EN)                              | Explanation (VN)                                |
|----------------------------|-----------------------------------------------|--------------------------------------------------|
| Type                       | Type of payment method used for the order     | Loại phương thức thanh toán được sử dụng cho đơn hàng |
| Days for shipping (real)   | Actual number of days to deliver the order    | Số ngày thực tế giao hàng                        |
| Days for shipment (scheduled) | Planned shipping time in days             | Số ngày dự kiến giao hàng                        |
| Benefit per order          | Profit made on the order                      | Lợi nhuận thu được trên mỗi đơn hàng             |
| Sales per customer         | Total sales generated from the customer       | Tổng doanh số từ khách hàng                      |
| Delivery Status            | Delivery timing status (on time, late, advance) | Trạng thái giao hàng (đúng hạn, trễ, sớm)     |
| Late_delivery_risk         | Binary flag indicating risk of late delivery  | Cờ cho biết đơn hàng có nguy cơ giao trễ         |
| Category Id                | Unique identifier of the product category     | Mã định danh danh mục sản phẩm                   |
| Category Name              | Name of the product category                  | Tên danh mục sản phẩm                            |
| Customer City              | City of the customer                          | Thành phố của khách hàng                         |
| Customer Country           | Country of the customer                       | Quốc gia của khách hàng                          |
| Customer Email             | Email address of the customer                 | Địa chỉ email của khách hàng                     |
| Customer Fname             | First name of the customer                    | Tên của khách hàng                               |
| Customer Id                | Unique identifier of the customer             | Mã định danh khách hàng                          |
| Customer Lname             | Last name of the customer                     | Họ của khách hàng                                |
| Customer Password          | Password (anonymized)                         | Mật khẩu (đã ẩn danh)                            |
| Customer Segment           | Segment the customer belongs to               | Phân khúc khách hàng                             |
| Customer State             | State/region of the customer                  | Tỉnh/Bang của khách hàng                         |
| Customer Street            | Street address of the customer                | Địa chỉ đường phố của khách hàng                 |
| Customer Zipcode           | Zipcode of the customer                       | Mã bưu điện của khách hàng                       |
| Department Id              | Unique identifier of the department           | Mã định danh phòng ban                           |
| Department Name            | Name of the department                        | Tên phòng ban                                    |
| Latitude                   | Latitude of shipping location                 | Vĩ độ nơi giao hàng                              |
| Longitude                  | Longitude of shipping location                | Kinh độ nơi giao hàng                            |
| Market                     | Market category of the order                  | Thị trường của đơn hàng                          |
| Order City                 | City where order was placed                   | Thành phố đặt đơn hàng                           |
| Order Country              | Country where order was placed                | Quốc gia đặt đơn hàng                            |
| Order Customer Id          | Customer ID linked to the order               | Mã khách hàng của đơn hàng                       |
| Order Date                 | Date when the order was placed                | Ngày đặt đơn hàng                                |
| Order Id                   | Unique order identifier                       | Mã định danh đơn hàng                            |
| Order Item Cardprod Id     | Product ID used in the order                  | Mã sản phẩm trong đơn hàng                       |
| Order Item Discount        | Discount value applied to item                | Số tiền chiết khấu trên sản phẩm                 |
| Order Item Discount Rate   | Rate of discount applied                      | Tỷ lệ chiết khấu                                  |
| Order Item Id              | Unique ID for the order item                  | Mã định danh mục đơn hàng                        |
| Order Item Product Price   | Price of the product                          | Giá sản phẩm                                     |
| Order Item Profit Ratio    | Profit ratio for the item                     | Tỷ suất lợi nhuận sản phẩm                       |
| Order Item Quantity        | Quantity of the product ordered               | Số lượng sản phẩm đặt                            |
| Sales                      | Total sales amount                            | Tổng số tiền bán được                            |
| Order Item Total           | Total amount for the order item               | Tổng tiền mục đơn hàng                           |
| Order Profit Per Order     | Profit per order                              | Lợi nhuận trên mỗi đơn hàng                      |
| Order Region               | Region where the order was placed             | Khu vực đặt đơn hàng                             |
| Order State                | State of the order placement                  | Tỉnh/Bang đặt đơn                                |
| Order Status               | Status of the order                           | Trạng thái đơn hàng                              |
| Order Zipcode              | Zip code of the order location                | Mã bưu điện nơi đặt hàng                         |
| Product Card Id            | Card ID of the product                        | Mã thẻ sản phẩm                                  |
| Product Category Id        | Category ID of the product                    | Mã danh mục sản phẩm                             |
| Product Description        | Product description (missing data)            | Mô tả sản phẩm (bị thiếu dữ liệu)                |
| Product Image              | Image URL of the product                      | URL hình ảnh sản phẩm                            |
| Product Name               | Name of the product                           | Tên sản phẩm                                     |
| Product Price              | Price of the product                          | Giá sản phẩm                                     |
| Product Status             | Status flag of the product                    | Trạng thái sản phẩm                              |
| Shipping Date              | Date the order was shipped                    | Ngày đơn hàng được gửi đi                        |
| Shipping Mode              | Shipping mode used (Standard, Express, etc.)  | Phương thức vận chuyển                           |

</details>

<details>
<summary><strong>III. Design Thinking</strong></summary>

### Step 1: Empathize

<img width="921" height="516" alt="image" src="https://github.com/user-attachments/assets/f375ce83-26f9-4850-b437-3e01a69e9d64" />

<img width="921" height="514" alt="image" src="https://github.com/user-attachments/assets/bdb3b33a-3005-4f4b-a06f-e8119fe74b1f" />

### Step 2: Stakeholder Journey

<img width="921" height="515" alt="image" src="https://github.com/user-attachments/assets/01f8b4ff-e4dd-4415-8ef0-c0ccf21e2615" /> 

<img width="921" height="515" alt="image" src="https://github.com/user-attachments/assets/c93519a4-f3da-4500-b3b2-cc6f9640cf9b" />

### Step 3: Ideate – Brainstorming 

<img width="921" height="515" alt="image" src="https://github.com/user-attachments/assets/483ce1d0-5c6b-4df4-bd47-bddde3e9f531" />

</details>

<details>
<summary><strong>IV. Visualization</strong></summary>

### 1. Overview Dashboard

<img width="921" height="524" alt="image" src="https://github.com/user-attachments/assets/4c4f5b7e-a682-4596-9fca-a826ad2a28fb" />

#### ✅ Insights

##### 1. Overall Performance

- **Total Revenue** reached **$36.78M**, showing a slight increase of **+0.91% YoY**.
- **Total Profit** hit **$3.97M**, with a year-over-year growth of **+0.86%**.
- **Total Orders** recorded **65.75K**, marking a **+3.34% increase vs. LY**.

##### 2. Business Trend Over Time

- Revenue remained stable throughout the year, with a peak in **January ($3.46M)** and a low in **December ($2.60M)**.
- The revenue trend indicates a **declining pattern** toward year-end, especially from **October to December**.

##### 3. Shipping & Order Fulfillment

- **Average shipping days** hovered between **3.46 to 3.54 days** across the year, with minor fluctuations.
- Order volume was highest in **January (7.43K orders)** and consistently above **5K** in most months, suggesting strong baseline demand.

##### 4. Revenue by Market

- The top contributing market is **Europe (29.56%)**, followed by **Pacific Asia (27.94%)** and **USCA (22.49%)**.
- **LATAM** accounts for the smallest portion at **6.24%**, indicating potential for market development.

##### 5. Revenue by Product Category

- **Fishing** leads with **$6.9M**, followed by **Cleats ($4.4M)** and **Camping & Hiking ($4.1M)**.
- Categories such as **Computers ($0.7M)** and **Shop by Sport ($1.3M)** contribute minimally and may need strategic review.

---

📌 *Recommendation: Focus on boosting Q4 performance, optimizing delivery time, and expanding lower-performing markets/categories for better growth.*

### 2. Finacial Report

<img width="921" height="526" alt="image" src="https://github.com/user-attachments/assets/b034bd3c-dc64-4cb7-ab3f-ead4eaac6102" />

#### ✅ Insights

##### 1. Financial Overview

- **Total Revenue**: **$36.78M**, matching figures from the Overview page.
- **Total Profit**: **$3.97M**, with a **Profit Margin** of **10.78%**.
- **Total Expense**: **$32.82M**, indicating a high cost base.

##### 2. Revenue and Profit Trends

- Revenue dropped significantly in **2018**, falling **-9.9% YoY** to **$3.3M**, down from **$11.81M** in 2017.
- Revenue was highest in **2015 ($12.34M)** and declined year-over-year, signaling potential structural or market issues.

##### 3. Country-Level Insights

- **Top 3 countries** by revenue:
  - **USA**: **$4.9M**
  - **France**: **$2.9M**
  - **Mexico**: **$2.6M**
- These markets represent key contributors and may offer opportunities for further expansion.

##### 4. Department-Level Performance

| Department         | Revenue     | Profit      | Margin    |
|--------------------|-------------|-------------|-----------|
| Fan Shop           | $17.1M      | $1.83M      | 10.72%    |
| Apparel            | $7.98M      | $0.88M      | 11.06%    |
| Golf               | $4.61M      | $0.50M      | 10.79%    |
| Footwear           | $4.01M      | $0.41M      | 10.24%    |
| Fitness            | $0.40M      | $0.05M      | **11.72%** (highest margin) |

- **Fan Shop** is the **top-performing department** by revenue and profit.
- **Fitness** yields the **highest profit margin** (11.72%), despite modest revenue.

##### 5. Payment Behavior

- Most revenue is generated via:
  - **Transfer**: **38.27%**
  - **Cash**: **27.72%**
  - **Payment**: **23.08%**
  - **Debit**: **10.94%**
- High reliance on **bank transfers** suggests a preference for formal payment channels.

##### 6. Top Products

- **Field & Stream Sports** is the top product with **$6.9M** revenue.
- Other top products include:
  - **Perfect Fitness Performance**: $4.4M
  - **Diamondback Women’s**: $4.1M

---

📌 *Recommendation: Investigate the steep revenue decline post-2017, optimize high-cost departments, and explore deeper penetration in high-performing countries and products.*

### 3. Delivery Report

<img width="921" height="526" alt="image" src="https://github.com/user-attachments/assets/6ff63f7b-ed36-4b17-b128-b0848c1aed3a" /> 

#### ✅ Insights

##### 1. Delivery Performance

- **Total Orders**: **65.75K**, nhưng chỉ **28.97K** được hoàn tất, cho thấy tỷ lệ hoàn thành đơn hàng khá thấp.
- **Average Shipping Day (Actual)**: **3.50 days**.
- **Late Delivery Rate**: **54.82%** – hơn một nửa đơn hàng đến trễ.
- **Average Late Shipping Day**: **1.62 days**, gây ảnh hưởng đến trải nghiệm khách hàng.

##### 2. Shipping Modes Breakdown

- **Standard Class** là phương thức giao hàng chủ yếu (**59.81%**), tiếp theo là:
  - **Second Class**: 19.43%
  - **First Class**: 15.33%
  - **Same Day**: 5.43%
- Phương thức **Standard Class** gắn liền với tỷ lệ giao trễ cao và số ngày giao hàng trung bình dài nhất (**4.00 days**).

##### 3. Delivery Status

- **Late Deliveries** chiếm **54.82%** tổng đơn.
- **Advance shipping** (giao sớm): 23.01%
- **On-time shipping**: chỉ **17.83%** – rất thấp.
- **Shipping Canceled**: 4.34%

##### 4. Cancellation by Country

- **Top 5 countries** by shipping cancellations:
  - **USA**: 4.55K
  - **France**: 2.72K
  - **Mexico**: 2.43K
  - **Australia**: 2.08K
  - **Germany**: 1.97K

##### 5. Market-Level Delivery Analysis

| Market       | Avg. Shipping Day Plan | Avg. Shipping Day (Actual) | Late Delivery Rate |
|--------------|-------------------------|-----------------------------|---------------------|
| Africa       | 3.0                     | 3.5                         | 54.13%              |
| LATAM        | 3.5                     | 3.5                         | 54.36%              |
| Pacific Asia | 2.9                     | 3.2                         | 55.30%              |
| Europe       | 2.9                     | 3.5                         | 54.95%              |
| USCA         | 3.0                     | 3.5                         | 54.84%              |

- **All markets exceed their planned shipping times**, especially **Europe and USCA**.
- **Late delivery rate > 54%** across all regions – critical issue needing attention.

---

📌 *Recommendation: Review fulfillment processes, improve logistics coordination for Standard Class, and implement predictive delay alerts to reduce late deliveries.*

### 4. Customer Report

<img width="921" height="526" alt="image" src="https://github.com/user-attachments/assets/b783ce83-db98-49e7-8033-f3db2bca8b47" />

#### ✅ Insights

##### 1. Customer Overview

- **Total Customers**: **20.65K**, increased by **+11.46%** compared to last year.  
- **Customer Segments**:
  - **Corporate**: 51.91%
  - **Consumer**: 30.36%
  - **Home Office**: 17.73%  
- Corporate is the main customer group, accounting for over half of total revenue and orders.

##### 2. Orders and Revenue by Segment

- **Total Revenue**: **$36.78M**
  - Corporate: $19.09M (51.91%)
  - Consumer: $11.16M (30.36%)
  - Home Office: $6.53M (17.73%)
- **Completed Orders**: **28.97K**
  - Corporate: 51.79%
  - Consumer: 30.32%
  - Home Office: 17.9%
- The proportional structure between orders and revenue across segments is **very consistent**, indicating relatively uniform average spending.

##### 3. Customer Behavior by Payment Type

- **Top payment methods**:
  - **Debit**: 9.8K customers (47.5%)
  - **Transfer**: 8.3K (40.2%)
  - **Payment**: 7.6K (36.8%)
  - **Cash**: 4.4K (21.3%)
- **Debit and Transfer** are the dominant payment methods — showing a strong preference for cashless transactions among customers.

##### 4. Customer Breakdown by Segment and Type

- The **Consumer segment** uses the widest variety of payment methods:
  - 7.0K use Debit
  - 5.3K use Payment
  - 5.8K use Transfer
  - 3.0K use Cash
- **Corporate and Home Office** segments are smaller in scale but still show a fairly diverse distribution of payment methods.

##### 5. Top Countries by Customer Count

- **USA**: 6.1K  
- **France**: 4.2K  
- **Mexico**: 3.7K  
- **Australia**: 3.6K  
- **Germany**: 3.2K  
- Customers in the **top 5 countries** represent a significant share and should continue to be prioritized with personalized customer care strategies in these key markets.

---

📌 *Recommendation: Focus on nurturing the Corporate segment – the primary customer group. Promote cashless payment methods and maintain growth momentum in core countries.*

### 5. Detail

<img width="921" height="520" alt="image" src="https://github.com/user-attachments/assets/82096891-b5b6-4ad2-a397-6f14ef8a3809" />

</details>

<details>
<summary><strong>V. Insights and Recommendation</strong></summary>

---

### 🔍 Business Summary

- **Total Revenue**: $36.78M | **Total Profit**: $3.97M | **Profit Margin**: 10.78%
- **Total Orders**: 65.75K | **Completed Orders**: 28.97K
- **Customer Count**: 20.65K ▲ 11.46% vs LY

---

### 📈 Key Insights

#### 1. Revenue & Profit Trends
- Revenue decreased significantly over time, from $12.3M in 2015 to just $0.3M in 2018 (▼9.9% YoY).
- **Fan Shop** is the top department by revenue ($17.1M) and profit ($1.83M), while **Fitness** has the highest profit margin (11.72%).
- **Top-selling product**: Field & Stream Sports ($6.9M).

#### 2. Delivery Performance
- Over **54.8% of orders are delivered late**, with an average delay of **1.62 days**.
- **Standard Class** (59.8% of orders) has the longest average delivery time (4.0 days).
- All regions missed their planned shipping time — especially Europe and USCA.
- High shipping cancellation in **USA, France, Mexico**.

#### 3. Customer Segment Behavior
- **Corporate customers** generate 52% of both revenue and completed orders.
- Most preferred payment methods: **Debit (47.5%)** and **Transfer (40.2%)**.
- **USA** is the largest customer base (6.1K), followed by France and Mexico.

---

## ✅ Recommendations

#### 📊 Business Growth
- Investigate the steep decline in revenue since 2017 and assess potential structural or strategic shifts.
- Focus investment and campaigns on **Fan Shop** and **top-performing products** like Field & Stream Sports.
- Explore expansion of **high-margin segments** like Fitness.

#### 🚚 Delivery Optimization
- Address the **high late delivery rate (54.82%)** by optimizing **Standard Class logistics**.
- Consider adjusting shipping plans or investing in faster fulfillment models (e.g., scale Same Day).
- Implement **early warning systems** for shipping delays and cancellations.

#### 👥 Customer Strategy
- Prioritize **Corporate segment** with loyalty programs or exclusive offers.
- Encourage **non-cash payments** through incentives to streamline operations.
- Personalize marketing campaigns in **top customer countries (USA, France, Mexico)** to boost retention and satisfaction.

---

📌 *Overall: To improve profitability and customer experience, the company must enhance delivery reliability, leverage strong customer segments, and invest in high-performing products while addressing revenue decline trends.*

</details>


