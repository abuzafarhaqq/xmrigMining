# xmrigMining
Mining Monero using xmrig

---

# Mining Monero Using Android
---

- [x] Update Termux.
- [x] Install Some Packages.
- [x] Clone From Xmrig Git Repo.
- [x] Make `build` directory and make `xmrig` package.

All Mining Codes:

```
apt update && apt upgrade -y;
apt install -y git wget proot build-essential cmake libmicrohttpd;
git clone https://github.com/xmrig/xmrig;
mkdir xmrig/build && cd xmrig/build && cmake -DWITH_HWLOC=OFF .. && make -j10
```

<!-- ./xmrig -a cryptonight -o stratum+tcp://xmr.pool.minergate.com:45700 -u yourmail@gmail.com -p x -3 // -u (user) -->
