# Function: <code>HUF_simpleQuickSort</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void HUF_simpleQuickSort(nodeElt *arr, int low, int high);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff817fe330)
Location: lib/zstd/compress/huf_compress.c:518
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
```
**Symbols:**

```
ffffffff817fe330-ffffffff817fe4cb: HUF_simpleQuickSort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void HUF_simpleQuickSort(nodeElt *arr, int low, int high);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff8183eb70)
Location: lib/zstd/compress/huf_compress.c:518
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
```
**Symbols:**

```
ffffffff8183eb70-ffffffff8183ed0b: HUF_simpleQuickSort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void HUF_simpleQuickSort(nodeElt *arr, int low, int high);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81890730)
Location: lib/zstd/compress/huf_compress.c:518
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
  - lib/zstd/compress/huf_compress.c:HUF_simpleQuickSort
```
**Symbols:**

```
ffffffff81890730-ffffffff818908cb: HUF_simpleQuickSort (STB_LOCAL)
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
