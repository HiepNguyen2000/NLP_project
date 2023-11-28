# NLP_project_Orcawise

## Pretrained model
- **Name of Pretrained Model:** Stanford OpenIE.
- **Description:** The OpenIEExtractor class uses Stanford OpenIE to extract relations from text. It employs a set of properties, including an affinity probability cap, to enhance the extraction process.

## Customed model
- **Name of Pretrained Model Used to Create the Custom Model:** BERT-base-uncased.
- **Description:** The CustomBertModel class fine-tunes the BERT model for relation classification.
- **How Much Data Needed to Create the Custom Model:** 


## Database
- **Databased used:** Mysql
- **Connection Setup:** The connection to the MySQL database is established using the mysql.connector library in Python. The connection details (host, port, user, password, database) are provided in the code.
- **How to run file:** run file: `python connect_my_sql.py`

## Execute the code
- Ensure you have the required libraries installed (`mysql.connector`, `torch`, `transformers`, etc.).
- Set up a MySQL server with the specified host, port, user, password, and database.
- Run the provided Python script to create a table and store predictions in the database. `python connect_my_sql.py`
