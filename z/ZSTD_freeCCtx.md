# Function: <code>ZSTD_freeCCtx</code>

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
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbeac)
Location: lib/zstd/compress.c:132
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_freeCStream
  - lib/zstd/compress.c:ZSTD_freeCStream
  - lib/zstd/compress.c:ZSTD_freeCDict
  - lib/zstd/compress.c:ZSTD_freeCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815c8b30-ffffffff815c8b91: ZSTD_freeCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e99e1)
Location: lib/zstd/compress.c:132
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_freeCStream
  - lib/zstd/compress.c:ZSTD_freeCStream
  - lib/zstd/compress.c:ZSTD_freeCDict
  - lib/zstd/compress.c:ZSTD_freeCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCDict
```
**Symbols:**

```
ffffffff815e6670-ffffffff815e66d6: ZSTD_freeCCtx (STB_GLOBAL)
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
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a300)
Location: lib/zstd/compress/zstd_compress.c:154
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8171a300-ffffffff8171a476: ZSTD_freeCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180f980)
Location: lib/zstd/compress/zstd_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff8180f980-ffffffff8180faf6: ZSTD_freeCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81850470)
Location: lib/zstd/compress/zstd_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff81850470-ffffffff818505df: ZSTD_freeCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_freeCCtx(ZSTD_CCtx *cctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a2030)
Location: lib/zstd/compress/zstd_compress.c:169
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream
  - lib/zstd/compress/zstd_compress.c:ZSTD_compress
```
**Symbols:**

```
ffffffff818a2030-ffffffff818a219f: ZSTD_freeCCtx (STB_GLOBAL)
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
