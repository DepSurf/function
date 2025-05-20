# Function: <code>ZSTD_flushStream</code>

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
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb800)
Location: lib/zstd/compress.c:3238
Inline: False
```
**Symbols:**

```
ffffffff815cb800-ffffffff815cba02: ZSTD_flushStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e9310)
Location: lib/zstd/compress.c:3238
Inline: False
```
**Symbols:**

```
ffffffff815e9310-ffffffff815e9523: ZSTD_flushStream (STB_GLOBAL)
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
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c680)
Location: lib/zstd/compress/zstd_compress.c:4840
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_flush_stream
```
**Symbols:**

```
ffffffff8171c680-ffffffff8171c6e4: ZSTD_flushStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811f00)
Location: lib/zstd/compress/zstd_compress.c:5960
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_flush_stream
```
**Symbols:**

```
ffffffff81811f00-ffffffff81811f64: ZSTD_flushStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852a00)
Location: lib/zstd/compress/zstd_compress.c:5960
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_flush_stream
```
**Symbols:**

```
ffffffff81852a00-ffffffff81852a64: ZSTD_flushStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_flushStream(ZSTD_CStream *zcs, ZSTD_outBuffer *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a45c0)
Location: lib/zstd/compress/zstd_compress.c:5960
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_flush_stream
```
**Symbols:**

```
ffffffff818a45c0-ffffffff818a4624: ZSTD_flushStream (STB_GLOBAL)
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
