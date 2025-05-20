# Function: <code>FSE_compressBound</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815acf20)
Location: lib/zstd/fse_compress.c:795
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_CStreamOutSize
  - lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound
```
**Symbols:**

```
ffffffff815acf20-ffffffff815acf30: FSE_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8a70)
Location: lib/zstd/fse_compress.c:795
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_endStream
  - lib/zstd/compress.c:ZSTD_flushStream
  - lib/zstd/compress.c:ZSTD_compressStream
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_CStreamOutSize
  - lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound
```
**Symbols:**

```
ffffffff815c8a70-ffffffff815c8a8a: FSE_compressBound (STB_GLOBAL)
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
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170edc0)
Location: lib/zstd/compress/fse_compress.c:622
Inline: False
```
**Symbols:**

```
ffffffff8170edc0-ffffffff8170ede0: FSE_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fde60)
Location: lib/zstd/compress/fse_compress.c:665
Inline: False
```
**Symbols:**

```
ffffffff817fde60-ffffffff817fde80: FSE_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e6b0)
Location: lib/zstd/compress/fse_compress.c:665
Inline: False
```
**Symbols:**

```
ffffffff8183e6b0-ffffffff8183e6d0: FSE_compressBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t FSE_compressBound(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff81890270)
Location: lib/zstd/compress/fse_compress.c:665
Inline: False
```
**Symbols:**

```
ffffffff81890270-ffffffff81890290: FSE_compressBound (STB_GLOBAL)
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
