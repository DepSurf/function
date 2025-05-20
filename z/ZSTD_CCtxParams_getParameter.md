# Function: <code>ZSTD_CCtxParams_getParameter</code>

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
size_t ZSTD_CCtxParams_getParameter(const ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81715f90)
Location: lib/zstd/compress/zstd_compress.c:770
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_getParameter
```
**Symbols:**

```
ffffffff81715f90-ffffffff817161be: ZSTD_CCtxParams_getParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_getParameter(const ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81809f30)
Location: lib/zstd/compress/zstd_compress.c:878
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_getParameter
```
**Symbols:**

```
ffffffff81809f30-ffffffff8180a198: ZSTD_CCtxParams_getParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_getParameter(const ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184a950)
Location: lib/zstd/compress/zstd_compress.c:878
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_getParameter
```
**Symbols:**

```
ffffffff8184a950-ffffffff8184ac4f: ZSTD_CCtxParams_getParameter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_CCtxParams_getParameter(const ZSTD_CCtx_params *CCtxParams, ZSTD_cParameter param, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189c510)
Location: lib/zstd/compress/zstd_compress.c:878
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_getParameter
```
**Symbols:**

```
ffffffff8189c510-ffffffff8189c80f: ZSTD_CCtxParams_getParameter (STB_GLOBAL)
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
