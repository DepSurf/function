# Function: <code>ZSTD_DUBT_findBestMatch</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_DUBT_findBestMatch(ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, size_t *offsetPtr, const U32 mls, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:231
Inline: False
```
**Symbols:**

```
ffffffff817321f0-ffffffff81732a03: ZSTD_DUBT_findBestMatch (STB_LOCAL)
ffffffff81e9eb67-ffffffff81e9ec69: ZSTD_DUBT_findBestMatch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_DUBT_findBestMatch(ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, size_t *offsetPtr, const U32 mls, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:231
Inline: False
```
**Symbols:**

```
ffffffff81845740-ffffffff8184609a: ZSTD_DUBT_findBestMatch (STB_LOCAL)
ffffffff820884a7-ffffffff820885f1: ZSTD_DUBT_findBestMatch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_DUBT_findBestMatch(ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, size_t *offsetPtr, const U32 mls, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:231
Inline: False
```
**Symbols:**

```
ffffffff818844c0-ffffffff81884e22: ZSTD_DUBT_findBestMatch (STB_LOCAL)
ffffffff821084e0-ffffffff82108600: ZSTD_DUBT_findBestMatch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_DUBT_findBestMatch(ZSTD_matchState_t *ms, const const BYTE * ip, const const BYTE * iend, size_t *offsetPtr, const U32 mls, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:231
Inline: False
```
**Symbols:**

```
ffffffff818d6080-ffffffff818d69e2: ZSTD_DUBT_findBestMatch (STB_LOCAL)
ffffffff821e664d-ffffffff821e676d: ZSTD_DUBT_findBestMatch.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
