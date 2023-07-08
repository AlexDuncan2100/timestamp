sudo yum update
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
source ~/.bashrc
command -v nvm
nvm install 16
node --version
npm --version

<!-- sudo yum update
sudo yum install -y amazon-linux-extras
sudo amazon-linux-extras enable glibc2.27
sudo yum clean metadata
sudo yum install -y glibc
rm -rf ~/.nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
source ~/.bashrc
nvm install 16 -->



npm install
npm start


/api/log
/api/logs


CREATE TABLE logs (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255),
  timestamp DATETIME
);