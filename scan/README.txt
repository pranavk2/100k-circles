make check_scan
make check_find_repeats

./cudaScan -m scan -n 500000
./cudaScan -m find_repeats -n 500000

