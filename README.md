# Fundamentals of Database Design & Information Systems

## Types of Information Systems & IT Landscapes

---

## 2. Enterprise Information Systems Mapping

### 1. Transaction Processing System (TPS)

A Transaction Processing System (TPS) records the daily, routine, operational transactions at SuperMart SA reliably and in real-time.

**Examples at the checkout counters:**

- Recording items sold through Point-of-Sale (POS) scanning
- Processing payments made by cash, card, EFT, or loyalty points
- Printing receipts and applying discounts or promotions
- Recording customer returns and refunds

**Examples at the inventory warehouse:**

- Recording stock received from suppliers using Goods Received Notes
- Recording stock dispatched from the warehouse to stores
- Updating inventory levels after every sale or stock movement
- Recording damaged or expired stock write-offs

These transactions must be recorded accurately and reliably to ensure correct stock levels, accurate financial records, and to prevent data loss.

---

### 2. Management Information Systems (MIS) & Decision Support Systems (DSS)

#### MIS for weekly sales performance

Store management uses a Management Information System (MIS) to obtain summarised reports from TPS data.

For example, a weekly sales report can show:

- Total sales per store
- Total sales per department
- Total sales per product category
- Sales compared to the previous week
- Sales compared to the monthly or weekly target

This helps managers monitor performance and identify underperforming stores, departments, or products.

#### DSS for promotion decisions

During a sudden drop in sales, a Decision Support System (DSS) helps management make semi-structured decisions.

A DSS can analyse:

- Historical sales data
- Current stock levels
- Competitor prices
- Customer buying trends
- Seasonal demand patterns

It can also run "what-if" scenarios. For example:

> If SuperMart SA runs a 20% discount on groceries this weekend, what will be the expected increase in sales and what will be the impact on profit?

This supports management in deciding whether or not to run the promotion.

---

### 3. Executive Support Systems (ESS)

The CEO needs high-level, summarised, and strategic information from an Executive Support System (ESS). This information is normally presented using dashboards, charts, and graphs.

**Examples include:**

- **Static reports:** Monthly and quarterly company-wide profit and loss reports, total revenue growth, and market share reports
- **Competitor data:** Competitor pricing, new store openings, and promotional activities
- **Long-term trend forecasts:** Three to five-year sales forecasts, economic trends, population growth in new areas for expansion, and changing consumer behaviour trends

This information helps the CEO make long-term strategic decisions, such as opening new stores, expanding into new markets, or changing the company's business strategy.

---

### 4. Knowledge Work Systems (KWS) & Office Automation Systems (OAS)

#### Knowledge Work System (KWS) example

Store designers and data analysts use a **Computer-Aided Design (CAD) system** to design new store layouts.

They can also use data analytics and Business Intelligence tools such as **Microsoft Power BI** to create product assortment models, analyse customer behaviour, and forecast product demand.

These systems help knowledge workers create new knowledge, designs, models, and business insights.

#### Office Automation System (OAS) example

Administration staff use **Microsoft 365**, including Microsoft Word, Excel, Outlook, and Teams, for:

- Creating documents
- Preparing spreadsheets
- Sending and receiving emails
- Scheduling meetings
- Communicating with other employees and departments

This automates routine office tasks and improves communication and productivity.

---

## 3. IT Landscape & Legacy Systems

### Why connecting old legacy systems to new cloud applications increases complexity

Connecting legacy systems that are approximately 15 years old to modern cloud applications increases complexity for the following reasons:

#### 1. Incompatibility

Legacy systems often use old programming languages, outdated databases, and old data formats that are not compatible with modern cloud applications and APIs.

Middleware or integration tools are therefore needed to translate and transfer data between the old and new systems. This makes the IT landscape more complicated and expensive to manage.

#### 2. Security and maintenance risks

Legacy systems may have outdated security features and may no longer be supported by their original vendors.

Connecting these systems to cloud applications can expose the organisation to security risks. They are also difficult to maintain or update because changing one part of the system may break the integration with other systems.

---

### Two ways to save costs using an IT Landscape Diagram

#### 1. End-of-Life (EOL) asset tracking

An IT Landscape Diagram shows all the organisation's software and hardware, including their versions and support expiry dates.

SuperMart SA can use the diagram to identify systems that are approaching End-of-Life before they fail or become a security risk.

This allows the company to plan and budget for replacements in advance, avoiding expensive emergency repairs, system failures, and unplanned downtime.

#### 2. Standardisation and removing duplication

An IT Landscape Diagram can reveal if different stores or departments are using different systems for the same purpose, such as multiple inventory applications.

SuperMart SA can standardise and use one system across the whole company. This reduces costs related to:

- Software licence fees
- Support and maintenance contracts
- Staff training
- System integration

Removing duplicate systems simplifies the IT landscape and reduces overall IT costs.

