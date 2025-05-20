# Function: <code>FSE_NCountWriteBound</code>

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
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac48a)
Location: lib/zstd/fse_compress.c:197
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff815ac450-ffffffff815ac466: FSE_NCountWriteBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c7f8f)
Location: lib/zstd/fse_compress.c:197
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff815c7f50-ffffffff815c7f70: FSE_NCountWriteBound (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8170e8bf)
Location: lib/zstd/compress/fse_compress.c:183
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8170e870-ffffffff8170e898: FSE_NCountWriteBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff817fd8cf)
Location: lib/zstd/compress/fse_compress.c:222
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff817fd870-ffffffff817fd89b: FSE_NCountWriteBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8183e12f)
Location: lib/zstd/compress/fse_compress.c:222
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8183e0d0-ffffffff8183e0fb: FSE_NCountWriteBound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_NCountWriteBound(unsigned int maxSymbolValue, unsigned int tableLog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/fse_compress.c (ffffffff8188fcef)
Location: lib/zstd/compress/fse_compress.c:222
Inline: True
Inline callers:
  - lib/zstd/compress/fse_compress.c:FSE_writeNCount
```
**Symbols:**

```
ffffffff8188fc90-ffffffff8188fcbb: FSE_NCountWriteBound (STB_GLOBAL)
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
