# Function: <code>ZSTD_initDCtx_internal</code>

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
void ZSTD_initDCtx_internal(ZSTD_DCtx *dctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8175365c)
Location: lib/zstd/decompress/zstd_decompress.c:243
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_createDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_createDCtx_advanced
```
**Symbols:**

```
ffffffff81750b30-ffffffff81750c2d: ZSTD_initDCtx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_initDCtx_internal(ZSTD_DCtx *dctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81874d50)
Location: lib/zstd/decompress/zstd_decompress.c:242
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
```
**Symbols:**

```
ffffffff81874d50-ffffffff81874e41: ZSTD_initDCtx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_initDCtx_internal(ZSTD_DCtx *dctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b5ab0)
Location: lib/zstd/decompress/zstd_decompress.c:242
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
```
**Symbols:**

```
ffffffff818b5ab0-ffffffff818b5b9d: ZSTD_initDCtx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_initDCtx_internal(ZSTD_DCtx *dctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81907670)
Location: lib/zstd/decompress/zstd_decompress.c:242
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress
```
**Symbols:**

```
ffffffff81907670-ffffffff8190775d: ZSTD_initDCtx_internal (STB_LOCAL)
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
