# Function: <code>ZSTD_insertDUBT1</code>

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
void ZSTD_insertDUBT1(ZSTD_matchState_t *ms, U32 curr, const BYTE *inputEnd, U32 nbCompares, U32 btLow, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:64
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
**Symbols:**

```
ffffffff81731c40-ffffffff817321e9: ZSTD_insertDUBT1 (STB_LOCAL)
ffffffff81e9eb11-ffffffff81e9eb67: ZSTD_insertDUBT1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_insertDUBT1(const ZSTD_matchState_t *ms, U32 curr, const BYTE *inputEnd, U32 nbCompares, U32 btLow, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:64
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
**Symbols:**

```
ffffffff81845030-ffffffff81845724: ZSTD_insertDUBT1 (STB_LOCAL)
ffffffff82088461-ffffffff820884a7: ZSTD_insertDUBT1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_insertDUBT1(const ZSTD_matchState_t *ms, U32 curr, const BYTE *inputEnd, U32 nbCompares, U32 btLow, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:64
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
**Symbols:**

```
ffffffff81883dd0-ffffffff818844a4: ZSTD_insertDUBT1 (STB_LOCAL)
ffffffff8210849a-ffffffff821084e0: ZSTD_insertDUBT1.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_insertDUBT1(const ZSTD_matchState_t *ms, U32 curr, const BYTE *inputEnd, U32 nbCompares, U32 btLow, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:64
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch
```
**Symbols:**

```
ffffffff818d5990-ffffffff818d6064: ZSTD_insertDUBT1 (STB_LOCAL)
ffffffff821e6607-ffffffff821e664d: ZSTD_insertDUBT1.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>ZSTD_matchState_t *ms</code> ➡️ <code>const ZSTD_matchState_t *ms</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
