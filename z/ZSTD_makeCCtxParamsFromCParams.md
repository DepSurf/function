# Function: <code>ZSTD_makeCCtxParamsFromCParams</code>

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
ZSTD_CCtx_params ZSTD_makeCCtxParamsFromCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81711f00)
Location: lib/zstd/compress/zstd_compress.c:203
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize_usingCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCParams
```
**Symbols:**

```
ffffffff81711f00-ffffffff81711fd1: ZSTD_makeCCtxParamsFromCParams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_CCtx_params ZSTD_makeCCtxParamsFromCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81806020)
Location: lib/zstd/compress/zstd_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize_usingCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCParams
```
**Symbols:**

```
ffffffff81806020-ffffffff81806147: ZSTD_makeCCtxParamsFromCParams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_CCtx_params ZSTD_makeCCtxParamsFromCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81846a10)
Location: lib/zstd/compress/zstd_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize_usingCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCParams
```
**Symbols:**

```
ffffffff81846a10-ffffffff81846b37: ZSTD_makeCCtxParamsFromCParams (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_CCtx_params ZSTD_makeCCtxParamsFromCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818985d0)
Location: lib/zstd/compress/zstd_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCStreamSize_usingCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCParams
```
**Symbols:**

```
ffffffff818985d0-ffffffff818986f7: ZSTD_makeCCtxParamsFromCParams (STB_LOCAL)
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
