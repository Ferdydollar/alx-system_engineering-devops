alias ls="rm *"
echo "hello $USER"
export PATH=$PATH:/action
echo $((`echo $PATH | grep -o ":/" | wc -l` + 1))
printenv
set
5-local_variables
export BEST="School"
echo $((128 + $TRUEKNOWLEDGE))
echo $((POWER / $DIVIDE))
echo $(($BREATH**$LOVE))
echo $((2#$BINARY))
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"
printf %x'\n' $DECIMAL
tr 'A-Za-z' 'N-ZA-Mn-za-m'
paste - - | cut -f1
