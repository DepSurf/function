# Function: <code>ZSTD_initCStream_internal</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_initCStream_internal(ZSTD_CStream *zcs, const void *dict, size_t dictSize, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bc90)
Location: lib/zstd/compress/zstd_compress.c:3980
Inline: False
```
**Symbols:**

```
ffffffff8171bc90-ffffffff8171bd0e: ZSTD_initCStream_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_initCStream_internal(ZSTD_CStream *zcs, const void *dict, size_t dictSize, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811440)
Location: lib/zstd/compress/zstd_compress.c:5096
Inline: False
```
**Symbols:**

```
ffffffff81811440-ffffffff818114be: ZSTD_initCStream_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_initCStream_internal(ZSTD_CStream *zcs, const void *dict, size_t dictSize, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81851f20)
Location: lib/zstd/compress/zstd_compress.c:5096
Inline: False
```
**Symbols:**

```
ffffffff81851f20-ffffffff81851f9e: ZSTD_initCStream_internal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_initCStream_internal(ZSTD_CStream *zcs, const void *dict, size_t dictSize, const ZSTD_CDict *cdict, const ZSTD_CCtx_params *params, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3ae0)
Location: lib/zstd/compress/zstd_compress.c:5096
Inline: False
```
**Symbols:**

```
ffffffff818a3ae0-ffffffff818a3b5e: ZSTD_initCStream_internal (STB_GLOBAL)
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
