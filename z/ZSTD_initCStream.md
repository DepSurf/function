# Function: <code>ZSTD_initCStream</code>

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
ZSTD_CStream *ZSTD_initCStream(ZSTD_parameters params, long long unsigned int pledgedSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc34e)
Location: lib/zstd/compress.c:3092
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815cc090-ffffffff815cc2d8: ZSTD_initCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ZSTD_CStream *ZSTD_initCStream(ZSTD_parameters params, long long unsigned int pledgedSrcSize, void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e9ea3)
Location: lib/zstd/compress.c:3092
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
```
**Symbols:**

```
ffffffff815e9be0-ffffffff815e9e2d: ZSTD_initCStream (STB_GLOBAL)
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
size_t ZSTD_initCStream(ZSTD_CStream *zcs, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bfe0)
Location: lib/zstd/compress/zstd_compress.c:4071
Inline: False
```
**Symbols:**

```
ffffffff8171bfe0-ffffffff8171c052: ZSTD_initCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_initCStream(ZSTD_CStream *zcs, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818117f0)
Location: lib/zstd/compress/zstd_compress.c:5187
Inline: False
```
**Symbols:**

```
ffffffff818117f0-ffffffff81811862: ZSTD_initCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_initCStream(ZSTD_CStream *zcs, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818522e0)
Location: lib/zstd/compress/zstd_compress.c:5187
Inline: False
```
**Symbols:**

```
ffffffff818522e0-ffffffff81852352: ZSTD_initCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_initCStream(ZSTD_CStream *zcs, int compressionLevel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3ea0)
Location: lib/zstd/compress/zstd_compress.c:5187
Inline: False
```
**Symbols:**

```
ffffffff818a3ea0-ffffffff818a3f12: ZSTD_initCStream (STB_GLOBAL)
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
