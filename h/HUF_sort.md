# Function: <code>HUF_sort</code>

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
void HUF_sort(nodeElt *huffNode, const U32 *count, U32 maxSymbolValue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815acf30)
Location: lib/zstd/huf_compress.c:389
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff815acf30-ffffffff815ad099: HUF_sort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void HUF_sort(nodeElt *huffNode, const U32 *count, U32 maxSymbolValue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815c8a90)
Location: lib/zstd/huf_compress.c:389
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff815c8a90-ffffffff815c8c00: HUF_sort (STB_LOCAL)
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81710c21)
Location: lib/zstd/compress/huf_compress.c:390
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff8180346d)
Location: lib/zstd/compress/huf_compress.c:547
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81843e5d)
Location: lib/zstd/compress/huf_compress.c:547
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81895a1d)
Location: lib/zstd/compress/huf_compress.c:547
Inline: True
Inline callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
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
</ul>
