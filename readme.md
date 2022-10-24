python solution by Keith R. Bergerstock

# description
used the package bitarray authored by ilanschnell@gmail.com
using bitarray the flag array size for primes (v) is 62564 bytes
note 500000 bits = 62500 bytes
elimination of floating point operations in algorithm
    replaced factor < square root of limit 
    with factor * factor < limit

# run instructions
# requires bitarray
pip install bitarray
python sieve.py --nPRIME_LIMIT --tmilliseconds --sPRINTFLAG
# defaults if not provided is 1000000 10000 False

# output
# machine  : ideacentre Y720 cube-13ISH
# processor : Intel(R) Core(TM) i7-7700 CPU @ 3.60GHz  
# OS : windows 10
# powershell, python 3.9.5
passes:  259  time: 10007.7466 Ms Avg: 38.6399 Ms  Limit:  1000000  count: 78498 valid: True
passes:  267  time: 10020.7429 Ms Avg: 37.5309 Ms  Limit:  1000000  count: 78498 valid: True
passes:  200  time: 10036.9393 Ms Avg: 50.1847 Ms  Limit:  1000000  count: 78498 valid: True
passes:  245  time: 10000.5822 Ms Avg: 40.8187 Ms  Limit:  1000000  count: 78498 valid: True
passes:  265  time: 10021.4118 Ms Avg: 37.8166 Ms  Limit:  1000000  count: 78498 valid: True

# Ubuntu 20.04.2 LTS
# WSL , python 3.8.10
passes:  275  time: 10049.2857 Ms Avg: 36.5429 Ms  Limit:  1000000  count: 78498 valid: True
passes:  257  time: 10025.9204 Ms Avg: 39.0114 Ms  Limit:  1000000  count: 78498 valid: True
passes:  275  time: 10033.2575 Ms Avg: 36.4846 Ms  Limit:  1000000  count: 78498 valid: True
passes:  282  time: 10011.1072 Ms Avg: 35.5004 Ms  Limit:  1000000  count: 78498 valid: True
passes:  256  time: 10021.6414 Ms Avg: 39.1470 Ms  Limit:  1000000  count: 78498 valid: True