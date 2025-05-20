# Function: <code>ZSTD_selectBlockCompressor</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c9f50)
Location: lib/zstd/compress.c:2322
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e7b25)
Location: lib/zstd/compress.c:2322
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_internal
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81712138)
Location: lib/zstd/compress/zstd_compress.c:2322
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff817183e0-ffffffff8171843d: ZSTD_selectBlockCompressor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818062b1)
Location: lib/zstd/compress/zstd_compress.c:2633
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff8180c3e0-ffffffff8180c4d3: ZSTD_selectBlockCompressor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81846ca4)
Location: lib/zstd/compress/zstd_compress.c:2633
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff8184ce80-ffffffff8184cf73: ZSTD_selectBlockCompressor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81898864)
Location: lib/zstd/compress/zstd_compress.c:2633
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress
```
**Symbols:**

```
ffffffff8189ea40-ffffffff8189eb33: ZSTD_selectBlockCompressor (STB_GLOBAL)
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
<b>Param added. </b>
<code>ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>strat, dictMode</code> ➡️ <code>strat, useRowMatchFinder, dictMode</code>
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
