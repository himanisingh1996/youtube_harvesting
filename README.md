This Python Script is meant to be run with StreamLit using following command
streamlit run YouTube_Data_Harvesting.py

Before running Streamlit app following prerequisites nmust be checked:

Connect MongoDB and check that MongoDB is available on localhost:27017

Create MySql credentials as
user: root
Password: 123456

Check that MySql is available on localhost:3306

#################################################################################
Error Disposal:
#################################################################################

In case program encounters DataType error 
Check that the Youtube channel should not have emojis in Video Name / Video Description.

