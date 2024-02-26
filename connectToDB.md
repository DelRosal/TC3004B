1. Install Oracle SQL extension (Oracle SQL Developer Extension for VSCode)
2. From OCI select Overview -> Oracle Databases -> Autonmous DB -> Select specific
3. Select DB connection, we will see a wallet. Click Download wallet
4. Create a password
5. It will download a .zip file Wallet_DBName
6. We need to add the .zip file (wallet), OUTSIDE of TC3004B but inside the codespace.
7. [unzip Wallet_DBName] (not necessary, but to see how it works)
8. Open extension 
9. Inside extension (create DB connection):
    1. name
    2. user: admin
        1. OCI (edit user) copy user code. Create file inside TC3004B 'SQLcommanfs.sql' 
    3. password: user passowrd from OCI
    2. Connection type: Cloud wallet (Cartera de cloud)
    3. Service: SQLPRACTICE_LOW
    4. Select file (wallet file)
10. REST ENABLE code to make the connection.


