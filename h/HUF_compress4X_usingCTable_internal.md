# Function: <code>HUF_compress4X_usingCTable_internal</code>

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
size_t HUF_compress4X_usingCTable_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable, int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff8170ff00)
Location: lib/zstd/compress/huf_compress.c:675
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compressCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff8170ff00-ffffffff81710111: HUF_compress4X_usingCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t HUF_compress4X_usingCTable_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable, int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff818025d0)
Location: lib/zstd/compress/huf_compress.c:1080
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compressCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff818025d0-ffffffff81802804: HUF_compress4X_usingCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t HUF_compress4X_usingCTable_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable, int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81842ec0)
Location: lib/zstd/compress/huf_compress.c:1080
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compressCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff81842ec0-ffffffff818430f4: HUF_compress4X_usingCTable_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t HUF_compress4X_usingCTable_internal(void *dst, size_t dstSize, const void *src, size_t srcSize, const HUF_CElt *CTable, int bmi2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81894a80)
Location: lib/zstd/compress/huf_compress.c:1080
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_compressCTable_internal
  - lib/zstd/compress/huf_compress.c:HUF_compress4X_usingCTable
```
**Symbols:**

```
ffffffff81894a80-ffffffff81894cb4: HUF_compress4X_usingCTable_internal (STB_LOCAL)
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
