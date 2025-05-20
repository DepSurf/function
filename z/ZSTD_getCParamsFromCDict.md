# Function: <code>ZSTD_getCParamsFromCDict</code>

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
ZSTD_compressionParameters ZSTD_getCParamsFromCDict(const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171b8b8)
Location: lib/zstd/compress/zstd_compress.c:3826
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
```
**Symbols:**

```
ffffffff8171b7c0-ffffffff8171b801: ZSTD_getCParamsFromCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCDict(const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e44b)
Location: lib/zstd/compress/zstd_compress.c:4919
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff818110b0-ffffffff818110f1: ZSTD_getCParamsFromCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCDict(const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ef5b)
Location: lib/zstd/compress/zstd_compress.c:4919
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff81851b90-ffffffff81851bd1: ZSTD_getCParamsFromCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCDict(const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0b1b)
Location: lib/zstd/compress/zstd_compress.c:4919
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal
```
**Symbols:**

```
ffffffff818a3750-ffffffff818a3791: ZSTD_getCParamsFromCDict (STB_GLOBAL)
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
