msg=$(free -h && top -bn1 && ss -tuna)
echo "$msg" >> log.txt
