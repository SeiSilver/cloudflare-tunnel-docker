# Setup  

### Reference Documentation

Cái này dùng để setup cloudflare tunnel với Self-host VPS mà không cần mở PORT FORWARDING

Lệnh này dùng để lấy public IP của bạn
``ssh
echo $(curl -s -4 https://cloudflare.com/cdn-cgi/trace | grep -E '^ip')
``
