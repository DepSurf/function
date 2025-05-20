# Function: <code>ZSTD_CCtx_init_compressStream2</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
size_t ZSTD_CCtx_init_compressStream2(ZSTD_CCtx *cctx, ZSTD_EndDirective endOp, size_t inSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171b270)
Location: lib/zstd/compress/zstd_compress.c:4308
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff8171b270-ffffffff8171b626: ZSTD_CCtx_init_compressStream2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_CCtx_init_compressStream2(ZSTD_CCtx *cctx, ZSTD_EndDirective endOp, size_t inSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81810a80)
Location: lib/zstd/compress/zstd_compress.c:5424
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff81810a80-ffffffff81810ebc: ZSTD_CCtx_init_compressStream2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_CCtx_init_compressStream2(ZSTD_CCtx *cctx, ZSTD_EndDirective endOp, size_t inSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81851560)
Location: lib/zstd/compress/zstd_compress.c:5424
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff81851560-ffffffff8185199c: ZSTD_CCtx_init_compressStream2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_CCtx_init_compressStream2(ZSTD_CCtx *cctx, ZSTD_EndDirective endOp, size_t inSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3120)
Location: lib/zstd/compress/zstd_compress.c:5424
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences
  - lib/zstd/compress/zstd_compress.c:ZSTD_compressStream2
```
**Symbols:**

```
ffffffff818a3120-ffffffff818a355c: ZSTD_CCtx_init_compressStream2 (STB_LOCAL)
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
