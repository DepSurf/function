# Function: <code>ZSTD_compressBegin_usingCDict_internal</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict_internal(const ZSTD_CCtx * cctx, const const ZSTD_CDict * cdict, const ZSTD_frameParameters fParams, const long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180e3a0)
Location: lib/zstd/compress/zstd_compress.c:4938
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
```
**Symbols:**

```
ffffffff8180e3a0-ffffffff8180e5e3: ZSTD_compressBegin_usingCDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict_internal(const ZSTD_CCtx * cctx, const const ZSTD_CDict * cdict, const ZSTD_frameParameters fParams, const long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184eeb0)
Location: lib/zstd/compress/zstd_compress.c:4938
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
```
**Symbols:**

```
ffffffff8184eeb0-ffffffff8184f0f5: ZSTD_compressBegin_usingCDict_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_compressBegin_usingCDict_internal(const ZSTD_CCtx * cctx, const const ZSTD_CDict * cdict, const ZSTD_frameParameters fParams, const long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a0a70)
Location: lib/zstd/compress/zstd_compress.c:4938
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingCDict_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced
```
**Symbols:**

```
ffffffff818a0a70-ffffffff818a0cb5: ZSTD_compressBegin_usingCDict_internal (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
