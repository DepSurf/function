# Function: <code>ZSTD_initStaticDCtx</code>

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
ZSTD_DCtx *ZSTD_initStaticDCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753645)
Location: lib/zstd/decompress/zstd_decompress.c:267
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dctx
```
**Symbols:**

```
ffffffff817511c0-ffffffff817512e7: ZSTD_initStaticDCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DCtx *ZSTD_initStaticDCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81875460)
Location: lib/zstd/decompress/zstd_decompress.c:266
Inline: True
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dctx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
```
**Symbols:**

```
ffffffff81875460-ffffffff8187557b: ZSTD_initStaticDCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DCtx *ZSTD_initStaticDCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b61b0)
Location: lib/zstd/decompress/zstd_decompress.c:266
Inline: True
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dctx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
```
**Symbols:**

```
ffffffff818b61b0-ffffffff818b62c7: ZSTD_initStaticDCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DCtx *ZSTD_initStaticDCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81907d70)
Location: lib/zstd/decompress/zstd_decompress.c:266
Inline: True
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dctx
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_initStaticDStream
```
**Symbols:**

```
ffffffff81907d70-ffffffff81907e87: ZSTD_initStaticDCtx (STB_GLOBAL)
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
