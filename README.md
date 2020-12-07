# local-storage-cache

Super simple package to cache data using local storage.
It only removes outdated data when calling `getCachedData` and the data has expired.

```
// To store data
cacheData('your-key', dataYouWantToStore, expireInMilliseconds);

// To get data
getCachedData('your-key');
```