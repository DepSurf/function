# Function: <code>ZSTD_reset_compressedBlockState</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
void ZSTD_reset_compressedBlockState(ZSTD_compressedBlockState_t *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171903a)
Location: lib/zstd/compress/zstd_compress.c:1431
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff81716d70-ffffffff81716dba: ZSTD_reset_compressedBlockState (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_reset_compressedBlockState(ZSTD_compressedBlockState_t *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e6af)
Location: lib/zstd/compress/zstd_compress.c:1588
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff8180af10-ffffffff8180af5a: ZSTD_reset_compressedBlockState (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_reset_compressedBlockState(ZSTD_compressedBlockState_t *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f1bb)
Location: lib/zstd/compress/zstd_compress.c:1588
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff8184b9b0-ffffffff8184b9fa: ZSTD_reset_compressedBlockState (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_reset_compressedBlockState(ZSTD_compressedBlockState_t *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0d7b)
Location: lib/zstd/compress/zstd_compress.c:1588
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_insertDictionary
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff8189d570-ffffffff8189d5ba: ZSTD_reset_compressedBlockState (STB_GLOBAL)
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
