Financial Data Analysis
SQL queries for analyzing credit card transactions, user demographics, and fraud detection patterns.
📊 Dataset
Three tables in testda schema:

users_data - Customer demographics, income, credit scores
cards_data - Credit card details, brands, security status
transactions_data - Transaction history, amounts, locations

🔍 Analysis Categories
1. Data Exploration

Record counts across tables
Data quality checks

2. User Demographics

Age group analysis with financial metrics
Gender-based spending patterns
Credit score distributions

3. Card Analysis

Brand distribution and credit limits
Dark web compromise detection
Card type comparisons

4. Transaction Patterns

Daily transaction volumes
Chip vs non-chip usage
Geographic transaction hotspots
Error rate analysis

5. Cross-Dataset Insights

Spending by demographics
Income vs transaction correlations

6. Fraud & Security

High-risk transaction detection
Error pattern analysis
Security breach impact

🚀 Usage
sql-- Run individual queries from the SQL file
-- Example: Check record counts
SELECT 'cards_data' as table_name, COUNT(*) FROM testda.cards_data
UNION ALL
SELECT 'users_data' as table_name, COUNT(*) FROM testda.users_data;
📈 Key Insights

User spending patterns by age/gender
Transaction security analysis
Fraud detection indicators
Geographic transaction trends
Credit card performance metrics

⚠️ Security Notice
Handle financial data according to compliance regulations. Ensure proper access controls and audit trails.
📄 License
MIT License - See LICENSE file for details.
