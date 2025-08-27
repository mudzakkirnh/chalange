Tujuan: Deploy "Hello World" HTML di EC2 otomatis via Terraform.
Arsitektur: 1 EC2 + 1 Security Group (HTTP 80), user-data memasang httpd & git,
            lalu git clone repo dan menyajikan challenge.html sebagai index.
Langkah: terraform init → validate → plan → apply → buka http://PUBLIC_IP
Cleanup: terraform destroy
