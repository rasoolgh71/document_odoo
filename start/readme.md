# start project odoo
git clone https://www.github.com/odoo/odoo --depth 1 --branch 17.0 my_odoo_project
* create file odoo.conf
* 
# run
```
python odoo-bin -c odoo.conf 
```

# run creat database new 
```run
python odoo-bin -c odoo.conf -d test_clean -u base
```