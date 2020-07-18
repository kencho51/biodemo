### VM info
Account: user-12@115.146.85.164  
Pw: arms-copy-hair

### Caution
Never directly pipe curl stdout to bash shell, unless from a trust people.

### functional test in docker?
for i in test_data/*;do docker run --rm -i biodemo-docker biodemo < $i; done

for i in test_data/*.fasta;do docker run --rm -i biodemo-docker biodemo < $i; done
