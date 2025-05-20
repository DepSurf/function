# Function: <code>ZSTD_resetSeqStore</code>

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
In lib/zstd/compress.c (ffffffff815c9fa8)
Location: lib/zstd/compress.c:43
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
In lib/zstd/compress.c (ffffffff815e7b7d)
Location: lib/zstd/compress.c:43
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
void ZSTD_resetSeqStore(seqStore_t *ssPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171816d)
Location: lib/zstd/compress/zstd_compress.c:2382
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
```
**Symbols:**

```
ffffffff81718440-ffffffff81718469: ZSTD_resetSeqStore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_resetSeqStore(seqStore_t *ssPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180bf40)
Location: lib/zstd/compress/zstd_compress.c:2714
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
```
**Symbols:**

```
ffffffff8180c4f0-ffffffff8180c519: ZSTD_resetSeqStore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_resetSeqStore(seqStore_t *ssPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184c9e5)
Location: lib/zstd/compress/zstd_compress.c:2714
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
```
**Symbols:**

```
ffffffff8184cf90-ffffffff8184cfb9: ZSTD_resetSeqStore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_resetSeqStore(seqStore_t *ssPtr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189e5a5)
Location: lib/zstd/compress/zstd_compress.c:2714
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
```
**Symbols:**

```
ffffffff8189eb50-ffffffff8189eb79: ZSTD_resetSeqStore (STB_GLOBAL)
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
