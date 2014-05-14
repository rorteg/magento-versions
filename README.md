magento-versions
================

Versions of Magento to work locally with the development of modules

run:
git clone git@github.com:rorteg/magento-versions.git

git checkout mage-1-5-master
rm app/etc/local.xml

Configure a vhost or use the native php server

Create a database for each version

Visit the server address in the browser and run the installation.

After a version installed, rerun the checkout for another version of the branch and 
repeat the process until you have installed all the versions on * different database.
