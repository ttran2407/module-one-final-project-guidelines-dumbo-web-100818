Stock Trading Application

This is a Stock Trading Application. Including Users, Transactions and Stocks

Relationship:

A User may has many stocks. Also, Stock may has many Users <many to many>
A User may has many Transactions but Transactions only belong to a specific Users.
A Stock may executes many times but each Transaction includes only one Stock

Description:

A User has its user name, password, money and a list of Stocks
A Stock has its ticker, value and its category
A transaction has its user, stock and its value

Function:

A User can buy, sell its stocks.
A User can see its portfolio - value
