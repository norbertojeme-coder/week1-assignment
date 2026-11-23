# Week 1 Assignment

## Day 1 - Kali Linux VM
- `day1/01-kali-running.png`: Kali VM running in VMware Fusion (used instead of VirtualBox because I'm on a Mac).
- `day1/02-password-changed.png`: Kali after changing my password with `passwd`. The password is not shown.

## Day 2 - Treasure Hunt
- `day2/clue01.png` to `day2/clue10.png`: one screenshot per clue, each showing the clue and the command or result used to solve it. Clue 7 has an extra screenshot, `clue07b.png`.

## Day 3 - Network Journey and Wireshark
Command screenshots:
- `day3/ping.png`: `ping` checked that the host was reachable and showed the reply times.
- `day3/traceroute.png`: `traceroute` showed the routers (hops) between my VM and the destination.
- `day3/dig.png`: `dig` looked up the domain's IP address through DNS.
- `day3/curl.png`: `curl -I` fetched the HTTP headers from the website.

Wireshark captures (one per command, named with `ws` at the end):
- `day3/pingws.png`: ICMP echo requests and replies from `ping`.
- `day3/traceroutews.png`: probe packets and ICMP "Time Exceeded" replies from the routers along the path.
- `day3/digws.png`: DNS query and response from `dig`.
- `day3/curlws.png`: HTTP request and response from `curl -I`.ls day1, ls day2,and ls day3
