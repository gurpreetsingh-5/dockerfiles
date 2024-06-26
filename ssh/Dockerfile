from ubuntu
run apt update ; apt install openssh-server -y
run useradd john
run echo "john:123" | chpasswd
run mkdir /run/sshd
copy xyz.sh ./
run chmod +x xyz.sh
cmd ["./xyz.sh"]
