# Node Exporter RPM builder

# How to build and install rpm on CentOS 8
```bash
# sudo yum install -y rpm-build
# git clone https://github.com/tgerov/node_exporter-rpm.git
# cd node_exporter-rpm/
# make
# sudo rpm -ivh rpmbuild/RPMS/x86_64/node-exporter-1.0.1-2.el8.x86_64.rpm 
# sudo systemctl enable --now node_exporter
````

# Install from prebuild RPM on CentOS 8
````bash
# rpm -ivh https://github.com/tgerov/node_exporter-rpm/releases/download/1.0.1-2/node-exporter-1.0.1-2.el8.x86_64.rpm
````

Based on https://github.com/utobi/prometheus-rpm/tree/master/node_exporter

