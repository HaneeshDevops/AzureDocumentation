# AzureDocumentation
```
sudo yum install -y docker
sudo systemctl start docker
sudo systemctl enable docker
sudo curl -L "https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
sudo zypper update -y
sudo zypper install -y maven
mvn -version
zypper install git
git clone https://github.com/HaneeshDevops/SpringBootEcommerceApplication.git
cd SpringBootEcommerceApplication
mvn install -DskipTests
 docker-compose up -d
```
#
```
wget http://mirror.olnevhost.net/pub/apache/maven/maven-3/3.2.5/binaries/apache-maven-3.2.5-bin.tar.gz
tar xzf apache-maven-3.2.5-bin.tar.gz
sudo mv apache-maven-3.2.5 /opt/
echo 'export PATH=/opt/apache-maven-3.2.5/bin:$PATH' >> ~/.bashrc
source ~/.bashrc

```
