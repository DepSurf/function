# Function: <code>ZSTD_compressBlock_btlazy2_extDict</code>

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
void ZSTD_compressBlock_btlazy2_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815c1660)
Location: lib/zstd/compress.c:2264
Inline: False
```
**Symbols:**

```
ffffffff815c1660-ffffffff815c1e89: ZSTD_compressBlock_btlazy2_extDict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_btlazy2_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d7eb0)
Location: lib/zstd/compress.c:2264
Inline: False
```
**Symbols:**

```
ffffffff815d7eb0-ffffffff815d86f4: ZSTD_compressBlock_btlazy2_extDict (STB_LOCAL)
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
size_t ZSTD_compressBlock_btlazy2_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:1408
Inline: False
```
**Symbols:**

```
ffffffff81ea2e7f-ffffffff81ea2f29: ZSTD_compressBlock_btlazy2_extDict.cold (STB_LOCAL)
ffffffff81742370-ffffffff81742c7d: ZSTD_compressBlock_btlazy2_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_btlazy2_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2073
Inline: False
```
**Symbols:**

```
ffffffff82089e85-ffffffff82089f25: ZSTD_compressBlock_btlazy2_extDict.cold (STB_LOCAL)
ffffffff818596b0-ffffffff8185a17a: ZSTD_compressBlock_btlazy2_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_btlazy2_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2073
Inline: False
```
**Symbols:**

```
ffffffff8210a2da-ffffffff8210a374: ZSTD_compressBlock_btlazy2_extDict.cold (STB_LOCAL)
ffffffff8189a280-ffffffff8189ad0b: ZSTD_compressBlock_btlazy2_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_btlazy2_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2073
Inline: False
```
**Symbols:**

```
ffffffff821e8447-ffffffff821e84e1: ZSTD_compressBlock_btlazy2_extDict.cold (STB_LOCAL)
ffffffff818ebe40-ffffffff818ec8cb: ZSTD_compressBlock_btlazy2_extDict (STB_GLOBAL)
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
