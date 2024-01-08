# commands
1. start docker
```
sudo systemctl start docker
```
3. start demo
 ```
clab deploy --topo demo.yml
```
5. stop demo
```
clab destroy --topo demo.yml
```
7. show demo graph
```
sudo containerlab graph --topo demo.yml
```
9. tcpdump
```
udo ip netns exec clab-frrlab-router3 tcpdump -U -n -i eth1 -w - | wireshark -k -i -
```
