# MyWarp's Maven Repository
Maven repository for external dependencies of the [MyWarp project](https://github.com/MyWarp/MyWarp) that do not have a (working) official repository and which cannot be used with JitPack due to build failures or missing git releases. `releases` contains releases artifacts, `snapshots` contains unreleased snapshots.

Note that this repository does **not** include MyWarp. Use [JitPack](https://jitpack.io/#MyWarp/mywarp) instead.

## Usage

### Grade
```gradle
repositories {
  maven { url 'https://raw.github.com/mywarp/repo/master/[REPO] }
}
```
### Maven
```xml
<repositories>
  <repository>
    <id>github-mywarp-repo</id>
    <url>https://raw.github.com/mywarp/repo/master/[REPO]</url>
  </repository>
</repositories>
```