# yumovh
Simple OVH BHS yum repo mirror

This script will make all the alterations you would need to update your centos system using the official and internal ovh bhs1 update server.<br />
this will allow you to update using the local server and not going online, in theory.. faster.
<br />
<br />
wget https://github.com/ZenithMediaCanada/yumovh/archive/master.zip -O ~/master.zip<br />
unzip ~/master.zip -d ~/ <br />
cp -uf ~/yumovh-master/*.repo /etc/yum.repos.d/ <br />
rm ~/master.zip <br />
rm -rf ~/yumovh-master<br />
done
<br />
<br />

Update: Added EPEL ovh.net mirrors
