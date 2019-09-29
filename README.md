# Revise Implementation of TCP TAHOE in ns-3

## Course Code: CO300

## Assignment: #14

### Overview
The previous versions of ns-3 contained the implementation of TCP Tahoe, but it was
removed when TCP codebase in ns-3 was significantly refactored to modularize
TcpSocketBase. It turns out that many researchers still use Tahoe to teach the fundamentals
of TCP. So adding Tahoe back in the mainline of ns-3 would be a valuable addition.


### Download ns-2 for TCP TAHOE implementation
[download ns-2.35](https://sourceforge.net/projects/nsnam/files/allinone/ns-allinone-2.35/ns-allinone-2.35.tar.gz/download)   

    go to ns-allinone-2.35/ns-2.35/tcp/linux/src
    tcp_tahoe.c is the required file



### References:
[1]Kevin Fall and Sally Floyd [Simulation-based Comparisons of Tahoe, Reno, and SACK TCP](https://www.icir.org/floyd/papers/sacks.pdf)



