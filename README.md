# FX_DJX_ETL_Wrangler
ETL application that automatically consumes 3rd party REST API (via HTTP request) for Alpha Vantage financial data, data ingests and wrangles and pushes as SQL into AWS RDS PostgreSQL database. Intended for use in AWS serverless Lambda environment (on NodeJS).

Utilises Mailgun to automatically sent out 'success' email.

Utilises JSON-SQL ORM for conversion of JSON to SQL structured data for RDBMS ingestion. Later version intended to include Sequelize ORM.

# External Links
For more information about Alpha Vantage, please visit their website: https://www.alphavantage.co/

For more information about Mailgun, please visit their website: https://www.mailgun.com/

For more information about AWS Lambda, please visit their website: https://aws.amazon.com/lambda/
