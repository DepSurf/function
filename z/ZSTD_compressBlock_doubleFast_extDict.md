# Function: <code>ZSTD_compressBlock_doubleFast_extDict</code>

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
void ZSTD_compressBlock_doubleFast_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c8ae0)
Location: lib/zstd/compress.c:1543
Inline: False
```
**Symbols:**

```
ffffffff815c8ae0-ffffffff815c8b26: ZSTD_compressBlock_doubleFast_extDict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_doubleFast_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e6620)
Location: lib/zstd/compress.c:1543
Inline: False
```
**Symbols:**

```
ffffffff815e6620-ffffffff815e666b: ZSTD_compressBlock_doubleFast_extDict (STB_LOCAL)
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
size_t ZSTD_compressBlock_doubleFast_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff817293d0)
Location: lib/zstd/compress/zstd_double_fast.c:502
Inline: False
```
**Symbols:**

```
ffffffff817293d0-ffffffff8172946a: ZSTD_compressBlock_doubleFast_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8181f0e0)
Location: lib/zstd/compress/zstd_double_fast.c:679
Inline: False
```
**Symbols:**

```
ffffffff8181f0e0-ffffffff8181f17a: ZSTD_compressBlock_doubleFast_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff8185f920)
Location: lib/zstd/compress/zstd_double_fast.c:679
Inline: False
```
**Symbols:**

```
ffffffff8185f920-ffffffff8185f9ba: ZSTD_compressBlock_doubleFast_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (ffffffff818b14e0)
Location: lib/zstd/compress/zstd_double_fast.c:679
Inline: False
```
**Symbols:**

```
ffffffff818b14e0-ffffffff818b157a: ZSTD_compressBlock_doubleFast_extDict (STB_GLOBAL)
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
