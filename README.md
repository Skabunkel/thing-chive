# thing-chive

|name|start|length|padding|format|type|
|----|-----|------|-------|------|----|
|id|0|4|no|byte|uint32|
|created-at|4|8|no|byte|int64|
|crypto-alg|12|2|no|byte|uint16|
|sign-alg|14|2|no|byte|uint16|
|sign|16|43|yes|ascii|hash|

59 bytes 
target is 64 

