# Function: <code>ZSTD_initStaticCCtx</code>

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
ZSTD_CCtx *ZSTD_initStaticCCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81715040)
Location: lib/zstd/compress/zstd_compress.c:103
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCStream
```
**Symbols:**

```
ffffffff81715040-ffffffff81715276: ZSTD_initStaticCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_initStaticCCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81808e40)
Location: lib/zstd/compress/zstd_compress.c:118
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCStream
```
**Symbols:**

```
ffffffff81808e40-ffffffff81809076: ZSTD_initStaticCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_initStaticCCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81849830)
Location: lib/zstd/compress/zstd_compress.c:118
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCStream
```
**Symbols:**

```
ffffffff81849830-ffffffff81849a66: ZSTD_initStaticCCtx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_CCtx *ZSTD_initStaticCCtx(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189b3f0)
Location: lib/zstd/compress/zstd_compress.c:118
Inline: False
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_init_cctx
  - lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCStream
```
**Symbols:**

```
ffffffff8189b3f0-ffffffff8189b626: ZSTD_initStaticCCtx (STB_GLOBAL)
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
