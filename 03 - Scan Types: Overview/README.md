# Scan Types


1. When port scanning with Nmap, there are `three basic scan` types. These are:

    - TCP Connect Scans (`-sT`)
    - SYN "Half-open" Scans (`-sS`)
    - UDP Scans (`-sU`)

2. Additionally there are several less common port scan types. These are:

    - TCP Null Scans (`-sN`)
    - TCP FIN Scans (`-sF`)
    - TCP Xmas Scans (`-sX`)

- Most of these (`with the exception of UDP scans`) are used for very similar purposes, however, the way that they work differs between each scan. This means that, whilst one of the first three scans are likely to be your go-to in most situations, it's worth bearing in mind that other scan types exist.
