# Function: <code>ZSTD_checkCParams</code>

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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b8063)
Location: lib/zstd/compress.c:148
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815af310-ffffffff815af372: ZSTD_checkCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d5548)
Location: lib/zstd/compress.c:148
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_resetCStream
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815caec0-ffffffff815caf27: ZSTD_checkCParams (STB_GLOBAL)
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817162a0)
Location: lib/zstd/compress/zstd_compress.c:1046
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff817162a0-ffffffff817163ba: ZSTD_checkCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180a2d0)
Location: lib/zstd/compress/zstd_compress.c:1163
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff8180a2d0-ffffffff8180a3ea: ZSTD_checkCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ad80)
Location: lib/zstd/compress/zstd_compress.c:1163
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff8184ad80-ffffffff8184ae9a: ZSTD_checkCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189c940)
Location: lib/zstd/compress/zstd_compress.c:1163
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced
```
**Symbols:**

```
ffffffff8189c940-ffffffff8189ca5a: ZSTD_checkCParams (STB_GLOBAL)
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
