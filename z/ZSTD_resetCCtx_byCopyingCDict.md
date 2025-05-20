# Function: <code>ZSTD_resetCCtx_byCopyingCDict</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81714a99)
Location: lib/zstd/compress/zstd_compress.c:1821
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2022
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
```
**Symbols:**

```
ffffffff818084d0-ffffffff81808770: ZSTD_resetCCtx_byCopyingCDict (STB_LOCAL)
ffffffff8207ddce-ffffffff8207de2b: ZSTD_resetCCtx_byCopyingCDict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2022
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
```
**Symbols:**

```
ffffffff81848ec0-ffffffff81849160: ZSTD_resetCCtx_byCopyingCDict (STB_LOCAL)
ffffffff820fe37e-ffffffff820fe3db: ZSTD_resetCCtx_byCopyingCDict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:2022
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict
```
**Symbols:**

```
ffffffff8189aa80-ffffffff8189ad20: ZSTD_resetCCtx_byCopyingCDict (STB_LOCAL)
ffffffff821dc4eb-ffffffff821dc548: ZSTD_resetCCtx_byCopyingCDict.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
