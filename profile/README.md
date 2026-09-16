<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img src="assets/logo-light.png" alt="TheAirTraffic" width="120">
  </picture>
</p>

<h1 align="center">TheAirTraffic</h1>

<p align="center">
  Global flight data aggregator and real-time tracking —<br>
  a community-driven ADS-B network built from receivers run by people like you.
</p>

<p align="center">
  <a href="https://globe.theairtraffic.com">Live Map</a> ·
  <a href="https://theairtraffic.com/how-to-feed">How To Feed</a> ·
  <a href="https://theairtraffic.com/myip">Feeder Status</a> ·
  <a href="https://theairtraffic.com/feeder-map">Feeder Map</a> ·
  <a href="https://theairtraffic.com/sync">MLAT Sync</a> ·
  <a href="https://theairtraffic.com/stats">Stats</a> ·
  <a href="https://grndcntrl.net/discord">Discord</a> ·
  <a href="https://www.reddit.com/r/TheAirTraffic/">Reddit</a>
</p>

---

### Share your receiver's data

Already running an ADS-B receiver? One command adds TheAirTraffic alongside your existing feeders, without disrupting them:

```bash
curl -L -o /tmp/tatfeed.sh https://raw.githubusercontent.com/TheAirTraffic/tat-feeder/master/install.sh
sudo bash /tmp/tatfeed.sh
```

New to this, or don't have a receiver yet? Start with the [how to feed](https://theairtraffic.com/how-to-feed) guide.

### Repositories

| | |
|---|---|
| **[tat-feeder](https://github.com/TheAirTraffic/tat-feeder)** | Install and update scripts for feeding from an existing receiver |
| **[mlat-client](https://github.com/TheAirTraffic/mlat-client)** | Multilateration client, for locating aircraft that broadcast no position |

### Once you're feeding

| | |
|---|---|
| [Feeder Status](https://theairtraffic.com/myip) | Confirm your receiver is getting through |
| [Feeder Map](https://theairtraffic.com/feeder-map) | Where the network's receivers are |
| [MLAT Sync Stats](https://theairtraffic.com/sync) | Which receivers yours is synchronised with |
| [Stats](https://theairtraffic.com/stats) | Network-wide coverage and totals |

### Community

Questions, feedback, or help getting a receiver going:

- [Discord](https://grndcntrl.net/discord)
- [r/TheAirTraffic](https://www.reddit.com/r/TheAirTraffic/)

### More aircraft than ADS-B alone

Many aircraft transmit Mode S without a position. With timing data from several receivers at once, multilateration works out where they are — so the more people feeding, the more the whole network sees.
