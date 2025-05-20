# Function: <code>ZSTD_compressBlock_fast</code>

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
void ZSTD_compressBlock_fast(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c73e0)
Location: lib/zstd/compress.c:1104
Inline: False
```
**Symbols:**

```
ffffffff815c73e0-ffffffff815c8143: ZSTD_compressBlock_fast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_fast(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d3110)
Location: lib/zstd/compress.c:1104
Inline: False
```
**Symbols:**

```
ffffffff815d3110-ffffffff815d3fd8: ZSTD_compressBlock_fast (STB_LOCAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_fast(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:186
Inline: False
```
**Symbols:**

```
ffffffff81e9d360-ffffffff81e9d95c: ZSTD_compressBlock_fast.cold (STB_LOCAL)
ffffffff8172b290-ffffffff8172d0d0: ZSTD_compressBlock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_fast(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (ffffffff818279e0)
Location: lib/zstd/compress/zstd_fast.c:335
Inline: False
```
**Symbols:**

```
ffffffff818279e0-ffffffff81827aca: ZSTD_compressBlock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_fast(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (ffffffff818681d0)
Location: lib/zstd/compress/zstd_fast.c:335
Inline: False
```
**Symbols:**

```
ffffffff818681d0-ffffffff818682be: ZSTD_compressBlock_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBlock_fast(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (ffffffff818b9d90)
Location: lib/zstd/compress/zstd_fast.c:335
Inline: False
```
**Symbols:**

```
ffffffff818b9d90-ffffffff818b9e7e: ZSTD_compressBlock_fast (STB_GLOBAL)
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
