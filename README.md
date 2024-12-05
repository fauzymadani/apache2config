# apache2config
to create site with custom root dir in ubuntu server with apache2, create new file in `/etc/apache2/sites-available/laravel.conf`.

after that set 
```bash
sudo a2ensite laravel.conf 
```
the restart apache2
