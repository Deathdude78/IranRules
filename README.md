# IranRules
A list of domains
proxy= [
port= { 
0-65535},
inboundTag= {
socks,
http,
socks2,
http2},
Protocol= {
tls,
http,
bittorent}
]
Block= [
ext:iran.dat:ads,
geosite:category-ads-all,
reject-list.txt
]
Direct= [
directdomainir.txt,
directipir.txt,
domains.txt,
ext:iran.dat:other,
geoip:ir,
regexp:.+\.ir$directipir.txt
]
