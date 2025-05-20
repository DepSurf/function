# Function: <code>ZSTD_CCtxParams_reset</code>

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
size_t ZSTD_CCtxParams_reset(ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a829)
Location: lib/zstd/compress/zstd_compress.c:249
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff817154c0-ffffffff8171552c: ZSTD_CCtxParams_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtxParams_reset(ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180ff12)
Location: lib/zstd/compress/zstd_compress.c:316
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff81809320-ffffffff8180938c: ZSTD_CCtxParams_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtxParams_reset(ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818509ee)
Location: lib/zstd/compress/zstd_compress.c:316
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff81849d10-ffffffff81849d7c: ZSTD_CCtxParams_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t ZSTD_CCtxParams_reset(ZSTD_CCtx_params *params);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a25ae)
Location: lib/zstd/compress/zstd_compress.c:316
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced
```
**Symbols:**

```
ffffffff8189b8d0-ffffffff8189b93c: ZSTD_CCtxParams_reset (STB_GLOBAL)
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
