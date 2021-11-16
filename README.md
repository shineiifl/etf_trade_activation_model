# etf_trade_activation_model
Model to predict the potential client for ETF trade activation

# PROBLEM STATEMENT :
        1. TO IDENTIFY EFFECTIVE CHANNEL(EMAIL, SMS, WHATSAPP) FOR CAMPAIGNING AND TO TARGET A SET OF CLIENTS THROUGH THAT EFFECTIVE CHANNEL.
        2. TO BUILD A PROPENSITY MODEL FOR THE CUSTOMERS WHO ARE LIKELY TO TRADE POST ETF OUT OF 3.18LAKH ETF OPTIN CUSTOMERS.

# FEATURES :
* Age
* sex
* income_per_annum
* occupation
* Z20
* app_status
* E2 channel
* iskarvy
* KRA
<br>
<br>
* number of logins in last year
* num_trades in last year
* months since last login
* months since last trade
* FAO segment trading client
* delivery segment trading client
* intraday segment trading client
* dp_holding
* ledger_balance

# PROCEDURE :
-->  Clients acquired from random campaigns who have optin for free stock are 3.18Lakh -> YES. Further, we have to bifurcate them into two segments :
  * I. New Clients
  * II. Old Clients

--> We need to get data from CLEVERTAP so that we get relevant features to the final dataset. Thus from CLEVERTAP we have to understand the activity of the client
    on mobile app post ETF acceptance.

--> Coming to the First Requirement, initially we have to analyse the extracted data from CLEVERTAP to understand which was the most effective medium (CHANNEL)
    on 3.18lakh customer base who have accepted ETF. After we find the effective channel and target a particular segment of clients using that effective
    channel for conversion.
    
--> Futher, we have 54k customers who are trading post accepting ETF out of 3.18Lakh customers. NOW... we have to build a machine learning model to find propensity
    of customers who are probable of trading post accepting ETF.








