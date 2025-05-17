The Holy Bible (King James Version) for PostgreSQL

Updated for Python 3

The repo comes with the following files:

Python script (kjv-psql.py), CSV files for each book of the Bible (created from XLSX files, exported as "CSV Comma Delimited")

The script will create a database called 'bible', create one table called 'kjv', then populate all 31102 verse in the KJV Bible.

To import the CSV files into your PostgreSQL instance run this command:

python3 kjv-psql.py

After import there should be 31102 verses stored. One Bible verse equals one record. 

Please do not assume that all verses are 100% accurate as typos may occur. Always consult with a printed KJV Bible.
