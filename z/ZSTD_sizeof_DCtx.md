# Function: <code>ZSTD_sizeof_DCtx</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_sizeof_DCtx(const ZSTD_DCtx *dctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81754275)
Location: lib/zstd/decompress/zstd_decompress.c:214
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
```
**Symbols:**

```
ffffffff81751150-ffffffff817511a0: ZSTD_sizeof_DCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_sizeof_DCtx(const ZSTD_DCtx *dctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81878855)
Location: lib/zstd/decompress/zstd_decompress.c:213
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
```
**Symbols:**

```
ffffffff818753d0-ffffffff81875420: ZSTD_sizeof_DCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_sizeof_DCtx(const ZSTD_DCtx *dctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b9605)
Location: lib/zstd/decompress/zstd_decompress.c:213
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
```
**Symbols:**

```
ffffffff818b6120-ffffffff818b6170: ZSTD_sizeof_DCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_sizeof_DCtx(const ZSTD_DCtx *dctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190b1c5)
Location: lib/zstd/decompress/zstd_decompress.c:213
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_sizeof_DStream
```
**Symbols:**

```
ffffffff81907ce0-ffffffff81907d30: ZSTD_sizeof_DCtx (STB_GLOBAL)
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
