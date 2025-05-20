# Function: <code>ZSTD_updateTree</code>

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
void ZSTD_updateTree(ZSTD_CCtx *zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b1c90)
Location: lib/zstd/compress.c:1724
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
```
**Symbols:**

```
ffffffff815b1c90-ffffffff815b204b: ZSTD_updateTree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_CCtx *zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc690)
Location: lib/zstd/compress.c:1724
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
  - lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS
```
**Symbols:**

```
ffffffff815cc690-ffffffff815cca69: ZSTD_updateTree (STB_LOCAL)
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
<summary>In <code>5.19</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t *ms, const BYTE *ip, const BYTE *iend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff81748140)
Location: lib/zstd/compress/zstd_opt.c:516
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff81748140-ffffffff817481c1: ZSTD_updateTree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t *ms, const BYTE *ip, const BYTE *iend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818698a0)
Location: lib/zstd/compress/zstd_opt.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff818698a0-ffffffff81869927: ZSTD_updateTree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t *ms, const BYTE *ip, const BYTE *iend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818aa510)
Location: lib/zstd/compress/zstd_opt.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff818aa510-ffffffff818aa597: ZSTD_updateTree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t *ms, const BYTE *ip, const BYTE *iend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818fc0d0)
Location: lib/zstd/compress/zstd_opt.c:551
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent
```
**Symbols:**

```
ffffffff818fc0d0-ffffffff818fc157: ZSTD_updateTree (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
