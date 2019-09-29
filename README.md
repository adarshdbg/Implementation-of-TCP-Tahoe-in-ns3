# Revise Implementation of TCP TAHOE in ns-3

## Course Code: CO300

## Assignment: #14

### Overview
CUBIC TCP is the default TCP in Linux since 2007. One of the ns-3 developers has
implemented CUBIC TCP in ns-3.  
 This project aims to revise the older implementation and
make it work on latest ns-3-dev. 


### Download ns-2 for CUBIC TCP implementation
[download ns-2.35](https://sourceforge.net/projects/nsnam/files/allinone/ns-allinone-2.35/ns-allinone-2.35.tar.gz/download)   

    go to ns-allinone-2.35/ns-2.35/tcp/linux/src
    tcp_cubic.c is the required file

or [click here](https://github.com/Saharsh007/Revise-Implementation-of-CUBIC-TCP-in-ns-3/tree/master/ns-2.35%20CUBIC%20TCP%20implementation)


### References:
[1] I. Rhee NCSU, L. Xu UNL, S. Ha Colorado, A Zimmermann, L. Eggert, R. Scheffenegger NetApp. [CUBIC for Fast Long-Distance Networks](https://tools.ietf.org/pdf/rfc8312.pdf)

[2] ns-3 CUBIC TCP code  

[tcp-cubic.cc](https://github.com/natale-p/ns-3-dev-git/blob/tcp-versions-updated/src/internet/model/tcp-cubic.cc)

[tcp-cubic.h](https://github.com/natale-p/ns-3-dev-git/blob/tcp-versions-updated/src/internet/model/tcp-cubic.h)


[3] [CUBIC TCP implementation in ns-2.35](https://github.com/NetSys/ups/blob/master/ns-allinone-2.35/ns-2.35/tcp/linux/src/tcp_cubic.c)

