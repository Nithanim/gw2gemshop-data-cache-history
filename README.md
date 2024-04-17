This repository contains the raw data for the guild wars 2 gemstore.
The data is a leveldb.
If the reader complains about missing `.sst` or whatever, rename `.ldb` to it.
Can be decoded with the help of [https://github.com/Nithanim/gw2-catalogue-archive](https://github.com/Nithanim/gw2-catalogue-archive)

The reason this exists is because it indirectly provides historical data of the guild wars 2 gem shop.
If you can decode it you can extract and reason about availability and pricing of buyable stuff in the gem store.

Ideas are:
* Times of most sales
* For limited-availability items: when might it be available again
* Items most and longest discounted
* Website similar to https://isthereanydeal.com/
* When consistent ingest is available: notifications
