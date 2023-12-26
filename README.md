#####################################################################################
This Python Script is meant to be run with StreamLit using following command        #
streamlit run YouTube_Data_Harvesting.py                                            #
                                                                                    #
Before running Streamlit app following prerequisites nmust be checked:              #
                                                                                    #
Connect MongoDB and check that MongoDB is available on localhost:27017              #
                                                                                    #
Create MySql credentials as                                                         #
user: root                                                                          #
Password: 123456                                                                    #
                                                                                    #
Check that MySql is available on localhost:3306                                     #
######################################################################################


############################### Advise ###############################################

Google Data API has restriction of 15,000 requests in 24 hours, therefore it is advised to not harvest channels with more than 15000 Videos.   




#######################################################################################


############################ Error Disposal ###########################################

In case program encounters DataType error 
Check that the Youtube channel should not have emojis in Video Name / Video Description.

In case program encounters Google API exhausted QuotaCheckError.RESOURCE_EXHAUSTED
Check that the Google API used to harvest Youtube data is enabled and not exhausted its limit for the day. To overcome the issue change the Google API in the Python Script.

#######################################################################################

################################ END of Read Me ############################################
