# Revise Implementation of TCP TAHOE in ns-3

## Course Code: CO300

## Assignment: #14

### Overview
The previous versions of ns-3 contained the implementation of TCP Tahoe, but it was
removed when TCP codebase in ns-3 was significantly refactored to modularize
TcpSocketBase. It turns out that many researchers still use Tahoe to teach the fundamentals
of TCP. So adding Tahoe back in the mainline of ns-3 would be a valuable addition.


### Download ns-3 for TCP TAHOE implementation
[download ns-3.23](https://www.nsnam.org/releases/ns-3-23/)   

    go to ns-allinone-3.23/ns-3.23/src/internet/model/
    tcp_tahoe.cc is the required file
    In ns3 version ns-3.23 the tcp tahoe is implemented which is take as a reference for 
    implementing tcp tahoe in current ns3 version.


### References:
[1]Kevin Fall and Sally Floyd [Simulation-based Comparisons of Tahoe, Reno, and SACK TCP](https://www.icir.org/floyd/papers/sacks.pdf)



