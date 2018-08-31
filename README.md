# StatsIO 🏅
[![Build status](https://img.shields.io/appveyor/ci/yucked/statsio/master.svg?longCache=true&style=for-the-badge&logo=appveyor&colorA=303030&colorB=72ffc9&label=Current+Build)](https://ci.appveyor.com/project/Yucked/statsio)

## `Usage:`

```cs
var client = new StatsClient("Client-ID", "Client-Secret");
await client.Statistics.CreateAsync("Stats-Id", "Username");
```

## `Current Roadmap:`

- Statistics Implementations:
    - [x] `Statistics#CreateAsync`
    - [ ] `Statistics#UpdateAsync`
    - [x] `Statistics$GetAsync`
    - [x] `Statistics#ShowUserStatsAsync`
    - [x] `Statistics#GetSectionAsync`
    - [x] `Statistics#LeaderboadsAsync`
- Achievements Implementations: 
    - [x] `Achievement#AllAsync`
    - [x] `Achievement#ManualAsync`
    - [x] `Achievement#DisplayUsersAsync`
- [x] Need to figure linking out :thinking:
- [x] Renamed project to something better.
- [x] Come up with better method names (?) :weary:
- [x] `APIException` class for handling HTTP exceptions ⚠️
