# Function: <code>ZSTD_compressBegin_usingDict</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b78ab)
Location: lib/zstd/compress.c:2754
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff815b8990-ffffffff815b8fba: ZSTD_compressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d4d90)
Location: lib/zstd/compress.c:2754
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff815d5e70-ffffffff815d649f: ZSTD_compressBegin_usingDict (STB_GLOBAL)
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
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81719340)
Location: lib/zstd/compress/zstd_compress.c:3390
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff81719340-ffffffff8171945c: ZSTD_compressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e9c0)
Location: lib/zstd/compress/zstd_compress.c:4474
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff8180e9c0-ffffffff8180eae6: ZSTD_compressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184f4d0)
Location: lib/zstd/compress/zstd_compress.c:4474
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff8184f4d0-ffffffff8184f5f6: ZSTD_compressBegin_usingDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingDict(ZSTD_CCtx *cctx, const void *dict, size_t dictSize, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1090)
Location: lib/zstd/compress/zstd_compress.c:4474
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff818a1090-ffffffff818a11b6: ZSTD_compressBegin_usingDict (STB_GLOBAL)
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
