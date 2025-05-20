# Function: <code>ZSTD_copyCCtx</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b7f20)
Location: lib/zstd/compress.c:348
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
```
**Symbols:**

```
ffffffff815b1670-ffffffff815b1c66: ZSTD_copyCCtx.part.0 (STB_LOCAL)
ffffffff815b1c70-ffffffff815b1c89: ZSTD_copyCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress.c (ffffffff815d5405)
Location: lib/zstd/compress.c:348
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
Direct callers:
  - lib/zstd/compress.c:ZSTD_resetCStream
```
**Symbols:**

```
ffffffff815cc070-ffffffff815cc66b: ZSTD_copyCCtx.part.0 (STB_LOCAL)
ffffffff815cc670-ffffffff815cc68e: ZSTD_copyCCtx (STB_GLOBAL)
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
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81716e10)
Location: lib/zstd/compress/zstd_compress.c:1981
Inline: False
```
**Symbols:**

```
ffffffff81716e10-ffffffff81716e6f: ZSTD_copyCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180afd0)
Location: lib/zstd/compress/zstd_compress.c:2207
Inline: False
```
**Symbols:**

```
ffffffff8180afd0-ffffffff8180b02f: ZSTD_copyCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184ba70)
Location: lib/zstd/compress/zstd_compress.c:2207
Inline: False
```
**Symbols:**

```
ffffffff8184ba70-ffffffff8184bacf: ZSTD_copyCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx *dstCCtx, const ZSTD_CCtx *srcCCtx, long long unsigned int pledgedSrcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189d630)
Location: lib/zstd/compress/zstd_compress.c:2207
Inline: False
```
**Symbols:**

```
ffffffff8189d630-ffffffff8189d68f: ZSTD_copyCCtx (STB_GLOBAL)
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
