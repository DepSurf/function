# Function: <code>ZSTD_seqToCodes</code>

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
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c8c20)
Location: lib/zstd/compress.c:563
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815c8c20-ffffffff815c8cec: ZSTD_seqToCodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e6780)
Location: lib/zstd/compress.c:563
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressSequences_internal
```
**Symbols:**

```
ffffffff815e6780-ffffffff815e6851: ZSTD_seqToCodes (STB_GLOBAL)
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
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81716e70)
Location: lib/zstd/compress/zstd_compress.c:2064
Inline: False
```
**Symbols:**

```
ffffffff81716e70-ffffffff81716fc8: ZSTD_seqToCodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180b040)
Location: lib/zstd/compress/zstd_compress.c:2297
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff8180b040-ffffffff8180b198: ZSTD_seqToCodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184bae0)
Location: lib/zstd/compress/zstd_compress.c:2297
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff8184bae0-ffffffff8184bc38: ZSTD_seqToCodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_seqToCodes(const seqStore_t *seqStorePtr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189d6a0)
Location: lib/zstd/compress/zstd_compress.c:2297
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics
```
**Symbols:**

```
ffffffff8189d6a0-ffffffff8189d7f8: ZSTD_seqToCodes (STB_GLOBAL)
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
