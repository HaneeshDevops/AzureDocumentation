# AzureDocumentation
## select SUSE Linux Enterprise Server 15 SP4 +Patching - Gen2

```
sudo zypper install -y docker
systemctl start docker
systemctl enable docker
sudo curl -L "https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
zypper update -y
zypper install -y maven
mvn -version
zypper install git
git clone https://github.com/HaneeshDevops/SpringBootEcommerceApplication.git
cd SpringBootEcommerceApplication
mvn install -DskipTests
 docker-compose up -d
```
