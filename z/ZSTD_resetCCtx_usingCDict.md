# Function: <code>ZSTD_resetCCtx_usingCDict</code>

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
size_t ZSTD_resetCCtx_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1888
Inline: False
```
**Symbols:**

```
ffffffff817148b0-ffffffff81714d5b: ZSTD_resetCCtx_usingCDict (STB_LOCAL)
ffffffff81e97202-ffffffff81e97263: ZSTD_resetCCtx_usingCDict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_resetCCtx_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81808780)
Location: lib/zstd/compress/zstd_compress.c:2104
Inline: False
```
**Symbols:**

```
ffffffff81808780-ffffffff81808ac7: ZSTD_resetCCtx_usingCDict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_resetCCtx_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81849170)
Location: lib/zstd/compress/zstd_compress.c:2104
Inline: False
```
**Symbols:**

```
ffffffff81849170-ffffffff818494b7: ZSTD_resetCCtx_usingCDict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_resetCCtx_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189ad30)
Location: lib/zstd/compress/zstd_compress.c:2104
Inline: False
```
**Symbols:**

```
ffffffff8189ad30-ffffffff8189b077: ZSTD_resetCCtx_usingCDict (STB_LOCAL)
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
