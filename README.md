# scrubs
Display Ceph scrub status.

To view scrub progress:
```
# ./scrubs
2023-11-29  =  (1)
2023-12-04  =  (1)
2023-12-19  =  (1)
2023-12-30  =  (3)
2023-12-31  ==  (5)
2024-01-01  ==  (5)
2024-01-02  ===  (7)
2024-01-03  =====  (11)
2024-01-04  ====  (10)
2024-01-05  =============  (28)
2024-01-06  ==================  (39)
2024-01-07  ===========================  (58)
2024-01-08  ======================================================================  (146)
2024-01-09  ==========  (22)
#
```

or deep scrub progress:
```
# ./scrubs --deep
2023-11-27  =  (1)
2023-12-02  =  (1)
2023-12-19  =  (1)
2023-12-24  =  (1)
2023-12-25  ==  (2)
2023-12-26  =  (1)
2023-12-27  =  (1)
2023-12-28  =  (1)
2023-12-29  =====  (5)
2023-12-30  =======  (6)
2023-12-31  ===========  (10)
2024-01-01  ==================  (16)
2024-01-02  =====================================  (32)
2024-01-03  ===================================  (30)
2024-01-04  ================================  (27)
2024-01-05  ====================================================  (44)
2024-01-06  ===================================================  (43)
2024-01-07  ======================================================  (46)
2024-01-08  ======================================================================  (59)
2024-01-09  ===========  (10)
#
```
