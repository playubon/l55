mv .gitignore .gitignore.bak ;
tar -zcvf vendor.tar.gz vendor/ ;split -b 49M vendor.tar.gz vendor.tar.gz ;rm vendor.tar.gz ;
