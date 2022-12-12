# terraform-installation


  sudo mkdir -p /opt/terraform
    2  cd /opt/terraform
    3  clear
    4  sudo yum install wget -y
    5  sudo wget https://releases.hashicorp.com/terraform/1.0.5/terraform_1.0.5_linux_amd64.zip
    6  sudo yum install unzip -y
    7  sudo unzip terraform_1.0.5_linux_amd64.zip
    8  sudo mv /opt/terraform/terraform /usr/bin/
    9  terraform -version
