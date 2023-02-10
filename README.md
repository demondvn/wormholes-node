# wormholes-node

  docker run -id -p 30303:30303 -p 8545:8545 -v /mnt/blockstore/wormholes:/wm/.wormholes --name wormholes wormholestech/wormholes:v1 
  docker exec -it wormholes /bin/bash

  nano /wm/.wormholes/wormholes/nodekey
###điền private key vào bỏ 2 ký tự  0x đi
  supervisorctl restart wormhole
