echo "Hello, World"
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail /etc/passwd
head /etc/passwd
head -3 iacta | tail -1
echo "Best School" > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'
ls -la > ls_cwd_content
tail -n 1 < iacta >> iacta
find . -type f -name "*.js" -delete
find . -type d -not -name '.' | wc -l
ls -t1 | head
sort | uniq -u
grep "root" /etc/passwd
grep -i "bin" /etc/passwd | wc -1
grep -iA 3 "root" /etc/passwd
grep -i -v "bin" /etc/passwd
grep '^[:alpha:]' /etc/ssh/sshd_config
tr "A" "Z" | tr "c" "e"
tr -d "Cc"
rev
cut -d ":" -f1,6 /etc/passwd | sort
0x02-shell_redirections
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f
cut -c 1 | paste -s -d ''
tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev



