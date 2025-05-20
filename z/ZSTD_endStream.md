# Function: <code>ZSTD_endStream</code>

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
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb410)
Location: lib/zstd/compress.c:3251
Inline: False
```
**Symbols:**

```
ffffffff815cb410-ffffffff815cb588: ZSTD_endStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e8770)
Location: lib/zstd/compress.c:3251
Inline: False
```
**Symbols:**

```
ffffffff815e8770-ffffffff815e8aab: ZSTD_endStream (STB_GLOBAL)
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
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c6f0)
Location: lib/zstd/compress/zstd_compress.c:4847
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_end_stream
```
**Symbols:**

```
ffffffff8171c6f0-ffffffff8171c789: ZSTD_endStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811f80)
Location: lib/zstd/compress/zstd_compress.c:5967
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_end_stream
```
**Symbols:**

```
ffffffff81811f80-ffffffff81812019: ZSTD_endStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852a80)
Location: lib/zstd/compress/zstd_compress.c:5967
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_end_stream
```
**Symbols:**

```
ffffffff81852a80-ffffffff81852b19: ZSTD_endStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_endStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a4640)
Location: lib/zstd/compress/zstd_compress.c:5967
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_end_stream
```
**Symbols:**

```
ffffffff818a4640-ffffffff818a46d9: ZSTD_endStream (STB_GLOBAL)
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
