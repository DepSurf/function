# Function: <code>ZSTD_BtGetAllMatches_selectMLS_extDict</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
U32 ZSTD_BtGetAllMatches_selectMLS_extDict(ZSTD_CCtx *zc, const BYTE *ip, const const BYTE * iHighLimit, const U32 maxNbAttempts, const U32 matchLengthSearch, ZSTD_match_t *matches, const U32 minMatchLen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b9b90)
Location: lib/zstd/zstd_opt.h:389
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
```
**Symbols:**

```
ffffffff815b9b90-ffffffff815b9d67: ZSTD_BtGetAllMatches_selectMLS_extDict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
U32 ZSTD_BtGetAllMatches_selectMLS_extDict(ZSTD_CCtx *zc, const BYTE *ip, const const BYTE * iHighLimit, const U32 maxNbAttempts, const U32 matchLengthSearch, ZSTD_match_t *matches, const U32 minMatchLen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815dfd20)
Location: lib/zstd/zstd_opt.h:389
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
```
**Symbols:**

```
ffffffff815dfd20-ffffffff815e0b1c: ZSTD_BtGetAllMatches_selectMLS_extDict (STB_LOCAL)
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
