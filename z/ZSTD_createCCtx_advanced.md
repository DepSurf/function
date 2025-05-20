# Function: <code>ZSTD_createCCtx_advanced</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cc011)
Location: lib/zstd/compress.c:109
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCCtx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e9b56)
Location: lib/zstd/compress.c:109
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCCtx
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
ZSTD_CCtx *ZSTD_createCCtx_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a770)
Location: lib/zstd/compress/zstd_compress.c:91
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8171a770-ffffffff8171a8a6: ZSTD_createCCtx_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_createCCtx_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180fe50)
Location: lib/zstd/compress/zstd_compress.c:106
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8180fe50-ffffffff8180ff8f: ZSTD_createCCtx_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_createCCtx_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81850930)
Location: lib/zstd/compress/zstd_compress.c:106
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff81850930-ffffffff81850a6b: ZSTD_createCCtx_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_createCCtx_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a24f0)
Location: lib/zstd/compress/zstd_compress.c:106
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff818a24f0-ffffffff818a262b: ZSTD_createCCtx_advanced (STB_GLOBAL)
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
