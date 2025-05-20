# Function: <code>ZSTD_compressBegin_usingCDict</code>

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
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b7f11)
Location: lib/zstd/compress.c:2914
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
```
**Symbols:**

```
ffffffff815b7dc0-ffffffff815b7ec6: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d53f6)
Location: lib/zstd/compress.c:2914
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
```
**Symbols:**

```
ffffffff815d52a0-ffffffff815d53ab: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
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
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171ba80)
Location: lib/zstd/compress/zstd_compress.c:3885
Inline: False
```
**Symbols:**

```
ffffffff8171ba80-ffffffff8171baae: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811190)
Location: lib/zstd/compress/zstd_compress.c:4988
Inline: False
```
**Symbols:**

```
ffffffff81811190-ffffffff818111be: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81851c70)
Location: lib/zstd/compress/zstd_compress.c:4988
Inline: False
```
**Symbols:**

```
ffffffff81851c70-ffffffff81851c9e: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict(ZSTD_CCtx *cctx, const ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3830)
Location: lib/zstd/compress/zstd_compress.c:4988
Inline: False
```
**Symbols:**

```
ffffffff818a3830-ffffffff818a385e: ZSTD_compressBegin_usingCDict (STB_GLOBAL)
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
