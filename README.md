readme.md
Welcome to the show. This endeavor aims to provide you with insights into the functioning of projects within a real-time environment.

The code has been meticulously crafted with careful consideration for various aspects. It not only nurtures your coding skills but also imparts a comprehensive comprehension of project structures.

Let's Start with requirement to complete the projects:-

You should have laptop with minimum 4 GB of RAM, i3 and above (Better to have 8GB with i5).
Local setup of spark. This is tricky so keep all things intact to work it properly.Download python 3.10.11 instead of python3.6 or python3.9 Use this link for clean setup :- https://youtu.be/4p7gX4DBLyc
PyCharm installed in the system. How to install:- https://youtu.be/pPYjX-9JAQY
MySQL workbench should also be installed to the system. How to install:- https://youtu.be/JEbTIXd61kc
GitHub account is good to have but not necessary.
You should have AWS account. How to create:- https://youtu.be/k7522oZQi9Y
Understanding of spark,sql and python is required.
Project structure:-
my_project/
├── docs/
│   └── readme.md
├── resources/
│   ├── __init__.py
│   ├── dev/
│   │    ├── config.py
│   │    └── requirement.txt
│   └── qa/
│   │    ├── config.py
│   │    └── requirement.txt
│   └── prod/
│   │    ├── config.py
│   │    └── requirement.txt
│   ├── sql_scripts/
│   │    └── table_scripts.sql
├── src/
│   ├── main/
│   │    ├── __init__.py
│   │    └── delete/
│   │    │      ├── aws_delete.py
│   │    │      ├── database_delete.py
│   │    │      └── local_file_delete.py
│   │    └── download/
│   │    │      └── aws_file_download.py
│   │    └── move/
│   │    │      └── move_files.py
│   │    └── read/
│   │    │      ├── aws_read.py
│   │    │      └── database_read.py
│   │    └── transformations/
│   │    │      └── jobs/
│   │    │      │     ├── customer_mart_sql_transform_write.py
│   │    │      │     ├── dimension_tables_join.py
│   │    │      │     ├── main.py
│   │    │      │     └──sales_mart_sql_transform_write.py
│   │    └── upload/
│   │    │      └── upload_to_s3.py
│   │    └── utility/
│   │    │      ├── encrypt_decrypt.py
│   │    │      ├── logging_config.py
│   │    │      ├── s3_client_object.py
│   │    │      ├── spark_session.py
│   │    │      └── my_sql_session.py
│   │    └── write/
│   │    │      ├── database_write.py
│   │    │      └── parquet_write.py
│   ├── test/
│   │    ├── scratch_pad.py.py
│   │    └── generate_csv_data.py
How to run the program in Pycharm:-

Open the pycharm editor.
Upload or pull the project from GitHub.
Open terminal from bottom pane.
Goto virtual environment and activate it. Let's say you have venv as virtual environament.i) cd venv ii) cd Scripts iii) activate (if activate doesn't work then use ./activate)
Create main.py as explained in my videos on YouTube channel.
You will have to create a user on AWS also and assign s3 full access and provide secret key and access key to the config file.
Run main.py from green play button on top right hand side.
If everything works as expected enjoy, else re-try.
Project Architecture:- Architecture

Database ER Diagram:- Architecture

If you get stuck, don't forget to my watch my youtube channel project playlist for better understanding of the flow. My youtube channel link:- https://www.youtube.com/channel/UCacvJAgrPTjSEdnZObMzpqQ
