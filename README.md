# Bank
This is Demo application to manage small bank made by windows form

## Requirements:
1. Sql Server 2014 or later.
2. .NET version 4.5 or later.

## How to Use:
1. restore database in Sql server from bank.bak this file continues database tables with simple data.
2. run bank.exe file.
3. the default andmin account user name is "admin" and password is "ad" you can change this data from Sql Server.

## Properties:
1. with this application you can add, edit, delete employers accounts from admin account.
2. admin also can delete customers accounts.
3. admin most accept every customer account added by employer.
4. admin can also print reports about employees, customers or transactions.
5. when any employee add new customer the admin receive notification about new customers when next time he login.
6. employees can add new customers, transfer money from customer account to other customer account or deposit from customer account.
7. every user most have an account and login with username and password.
8. every customer most have only one account in the same name.
9. in search box you can search in customers, employees or transactions data by name, id, date or any data field.

## Notes:
1. this application haven't options to configure server connection so database name most be "Bank" and don't change any tables name.
2. the server most be in the local machine and the type of connection to server is windows verification without password.
