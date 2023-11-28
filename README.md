# NLP_project_Orcawise

## Pretrained model
- **Name of Pretrained Model:** Stanford OpenIE
- **Description:** The OpenIEExtractor class uses Stanford OpenIE to extract relations from text. It employs a set of properties, including an affinity probability cap, to enhance the extraction process.
- **How to run file:** Install the required dependencies: `pip install -r requirements.txt` and run file: `python nlu_pretrained_model.py`

## Customed model
- **Name of Pretrained Model Used to Create the Custom Model:** BERT-base-uncased
- **Description:** The CustomBertModel class fine-tunes the BERT model for relation classification.
- **How Much Data Needed to Create the Custom Model:** 
- **How to run file:** Install the required dependencies: `pip install -r requirements.txt` and run file: `python nlu_custom_model.py`


## Database
- **Databased used:** Mysql
-  **Connection Setup:** The connection to the MySQL database is established using the mysql.connector library in Python. The connection details (host, port, user, password, database) are provided in the code.
