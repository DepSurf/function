# Function: <code>FSE_writeNCount_generic</code>

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
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ab800)
Location: lib/zstd/fse_compress.c:203
Inline: False
Direct callers:
  - lib/zstd/fse_compress.c:FSE_writeNCount
  - lib/zstd/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff815ab800-ffffffff815aba75: FSE_writeNCount_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7320)
Location: lib/zstd/fse_compress.c:203
Inline: False
Direct callers:
  - lib/zstd/fse_compress.c:FSE_writeNCount
  - lib/zstd/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff815c7320-ffffffff815c7580: FSE_writeNCount_generic (STB_LOCAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:190
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8170d480-ffffffff8170d741: FSE_writeNCount_generic (STB_LOCAL)
ffffffff81e95c95-ffffffff81e95dd1: FSE_writeNCount_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:233
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff817fc3d0-ffffffff817fc691: FSE_writeNCount_generic (STB_LOCAL)
ffffffff8207a9c3-ffffffff8207aaff: FSE_writeNCount_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:233
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8183cdc0-ffffffff8183d07e: FSE_writeNCount_generic (STB_LOCAL)
ffffffff820fb13b-ffffffff820fb26b: FSE_writeNCount_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_writeNCount_generic(void *header, size_t headerBufferSize, const short int *normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, unsigned int writeIsSafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:233
Inline: False
Direct callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8188e980-ffffffff8188ec3e: FSE_writeNCount_generic (STB_LOCAL)
ffffffff821d92a8-ffffffff821d93d8: FSE_writeNCount_generic.cold (STB_LOCAL)
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
