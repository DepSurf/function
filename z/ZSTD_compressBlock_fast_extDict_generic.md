# Function: <code>ZSTD_compressBlock_fast_extDict_generic</code>

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
void ZSTD_compressBlock_fast_extDict_generic(ZSTD_CCtx *ctx, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b40a0)
Location: lib/zstd/compress.c:1116
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff815b40a0-ffffffff815b4656: ZSTD_compressBlock_fast_extDict_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_fast_extDict_generic(ZSTD_CCtx *ctx, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d3fe0)
Location: lib/zstd/compress.c:1116
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff815d3fe0-ffffffff815d4628: ZSTD_compressBlock_fast_extDict_generic (STB_LOCAL)
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
size_t ZSTD_compressBlock_fast_extDict_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const U32 mls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:375
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff81729750-ffffffff8172b024: ZSTD_compressBlock_fast_extDict_generic (STB_LOCAL)
ffffffff81e9c700-ffffffff81e9d0e0: ZSTD_compressBlock_fast_extDict_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:548
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff81827ae0-ffffffff818289d6: ZSTD_compressBlock_fast_extDict_generic.constprop.0 (STB_LOCAL)
ffffffff8208308c-ffffffff82083468: ZSTD_compressBlock_fast_extDict_generic.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:548
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff818682d0-ffffffff8186917e: ZSTD_compressBlock_fast_extDict_generic.constprop.0 (STB_LOCAL)
ffffffff8210341d-ffffffff821037c9: ZSTD_compressBlock_fast_extDict_generic.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_fast.c (0)
Location: lib/zstd/compress/zstd_fast.c:548
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
  - lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict
```
**Symbols:**

```
ffffffff818b9e90-ffffffff818bad3e: ZSTD_compressBlock_fast_extDict_generic.constprop.0 (STB_LOCAL)
ffffffff821e158a-ffffffff821e1936: ZSTD_compressBlock_fast_extDict_generic.constprop.0.cold (STB_LOCAL)
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
</ul>
