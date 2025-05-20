# Function: <code>ZSTD_malloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff814ba490)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff814ba490-ffffffff814ba4a6: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff814ecd50)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff814ecd50-ffffffff814ecd66: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81500af0)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81500af0-ffffffff81500b06: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8152ec50)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8152ec50-ffffffff8152ec66: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8154fae0)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8154fae0-ffffffff8154faf6: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815cda50)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_createCDict_advanced
  - lib/zstd/compress.c:ZSTD_createCDict_advanced
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_resetCCtx_advanced
  - lib/zstd/compress.c:ZSTD_initCCtx
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815cda50-ffffffff815cda66: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815eb600)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_createCDict_advanced
  - lib/zstd/compress.c:ZSTD_createCDict_advanced
  - lib/zstd/compress.c:ZSTD_compressCCtx
  - lib/zstd/compress.c:ZSTD_compress_usingDict
  - lib/zstd/compress.c:ZSTD_compressBegin
  - lib/zstd/compress.c:ZSTD_resetCCtx_advanced
  - lib/zstd/compress.c:ZSTD_initCCtx
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815eb600-ffffffff815eb61b: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815d9710)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815d9710-ffffffff815d972b: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81644a10)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81644a10-ffffffff81644a2b: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffff80001065bae8)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffff80001065bae8-ffff80001065bb0c: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (c0805180)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
c0805180-c08051b0: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (c00000000080d0f8)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
c00000000080d0f8-c00000000080d138: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffe0004899a0)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffe0004899a0-ffffffe0004899ba: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815480c0)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815480c0-ffffffff815480d6: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815383a0)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815383a0-ffffffff815383b6: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81543e00)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81543e00-ffffffff81543e16: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ZSTD_malloc(size_t size, ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8155dc30)
Location: lib/zstd/zstd_common.c:69
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8155dc30-ffffffff8155dc46: ZSTD_malloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
