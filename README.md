# Levchenko-Ass1
#!/bin/bash
user="test"
dir=new-directory
if [ $UID -eq 0 ] && [ -d $dir ] && [ -n $user ];
then { sudo chown -R test:test $dir; }
fi
