# Function: <code>ZSTD_isSkippableFrame</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int ZSTD_isSkippableFrame(const void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818769a4)
Location: lib/zstd/decompress/zstd_decompress.c:380
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
```
**Symbols:**

```
ffffffff818758c0-ffffffff818758eb: ZSTD_isSkippableFrame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int ZSTD_isSkippableFrame(const void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b7749)
Location: lib/zstd/decompress/zstd_decompress.c:380
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
```
**Symbols:**

```
ffffffff818b6610-ffffffff818b663b: ZSTD_isSkippableFrame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int ZSTD_isSkippableFrame(const void *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81909309)
Location: lib/zstd/decompress/zstd_decompress.c:380
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_readSkippableFrame
```
**Symbols:**

```
ffffffff819081d0-ffffffff819081fb: ZSTD_isSkippableFrame (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
