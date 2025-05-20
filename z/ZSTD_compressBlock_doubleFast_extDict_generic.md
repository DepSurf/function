# Function: <code>ZSTD_compressBlock_doubleFast_extDict_generic</code>

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
void ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_CCtx *ctx, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c8150)
Location: lib/zstd/compress.c:1395
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff815c8150-ffffffff815c8ad6: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_CCtx *ctx, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e5c20)
Location: lib/zstd/compress.c:1395
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff815e5c20-ffffffff815e6611: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
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
size_t ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:357
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff81720fa0-ffffffff8172202f: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
ffffffff81e98a9a-ffffffff81e9a590: ZSTD_compressBlock_doubleFast_extDict_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:530
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff8181e1a0-ffffffff8181f03b: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
ffffffff82081254-ffffffff8208172a: ZSTD_compressBlock_doubleFast_extDict_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:530
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff8185e9c0-ffffffff8185f876: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
ffffffff821014c5-ffffffff8210196f: ZSTD_compressBlock_doubleFast_extDict_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_doubleFast_extDict_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_double_fast.c (0)
Location: lib/zstd/compress/zstd_double_fast.c:530
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
  - lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict
```
**Symbols:**

```
ffffffff818b0580-ffffffff818b1436: ZSTD_compressBlock_doubleFast_extDict_generic (STB_LOCAL)
ffffffff821df632-ffffffff821dfadc: ZSTD_compressBlock_doubleFast_extDict_generic.cold (STB_LOCAL)
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
