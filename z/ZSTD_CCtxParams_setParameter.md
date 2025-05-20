# Function: <code>ZSTD_CCtxParams_setParameter</code>

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
size_t ZSTD_CCtxParams_setParameter(ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817157e0)
Location: lib/zstd/compress/zstd_compress.c:585
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff817157e0-ffffffff81715e6b: ZSTD_CCtxParams_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_setParameter(ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818096b0)
Location: lib/zstd/compress/zstd_compress.c:678
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff818096b0-ffffffff81809de3: ZSTD_CCtxParams_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_setParameter(ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184a0b0)
Location: lib/zstd/compress/zstd_compress.c:678
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff8184a0b0-ffffffff8184a80c: ZSTD_CCtxParams_setParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_setParameter(ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189bc70)
Location: lib/zstd/compress/zstd_compress.c:678
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict
```
**Symbols:**

```
ffffffff8189bc70-ffffffff8189c3cc: ZSTD_CCtxParams_setParameter (STB_GLOBAL)
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
