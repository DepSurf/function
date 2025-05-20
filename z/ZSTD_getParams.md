# Function: <code>ZSTD_getParams</code>

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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b1480)
Location: lib/zstd/compress.c:3437
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff815b1480-ffffffff815b166c: ZSTD_getParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbe70)
Location: lib/zstd/compress.c:3437
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_compressBegin
```
**Symbols:**

```
ffffffff815cbe70-ffffffff815cc061: ZSTD_getParams (STB_GLOBAL)
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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c840)
Location: lib/zstd/compress/zstd_compress.c:5106
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_get_params
```
**Symbols:**

```
ffffffff8171c840-ffffffff8171c8a5: ZSTD_getParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81812140)
Location: lib/zstd/compress/zstd_compress.c:6124
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_get_params
```
**Symbols:**

```
ffffffff81812140-ffffffff818121a5: ZSTD_getParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852c40)
Location: lib/zstd/compress/zstd_compress.c:6124
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_get_params
```
**Symbols:**

```
ffffffff81852c40-ffffffff81852ca5: ZSTD_getParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a4800)
Location: lib/zstd/compress/zstd_compress.c:6124
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_get_params
```
**Symbols:**

```
ffffffff818a4800-ffffffff818a4865: ZSTD_getParams (STB_GLOBAL)
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
