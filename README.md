# oc-pni

## Allow 'Writeable' permissions on the following items

### Files:
1. upload/config.php
2. upload/admin/config.php

### Folders:
1. upload/system/cache/
2. upload/system/logs/
3. upload/image/
4. upload/image/cache/
5. upload/image/data/
6. upload/download

7. upload/temp_excelport/
8. upload/vqmod/

For more information check <<url>>

## Opencart folder update (in preperation for source control)<br/>

1. delete all contents in upload/image/cache, 'EXCEPT' index.html (empty file)
2. delete all contents in upload/image/data/pniimages
3. 

### Create symlink for image store
1. Navigate to <install_folder>/upload/image/data
2. issue the following command
	ln -s /home/imageupload/ pniimages
3. check using ls -la, pniimages should be shown as symlink
4. 
