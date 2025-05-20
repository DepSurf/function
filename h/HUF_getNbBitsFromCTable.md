# Function: <code>HUF_getNbBitsFromCTable</code>

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
U32 HUF_getNbBitsFromCTable(const HUF_CElt *CTable, U32 symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81803380)
Location: lib/zstd/compress/huf_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff81803380-ffffffff8180339a: HUF_getNbBitsFromCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
U32 HUF_getNbBitsFromCTable(const HUF_CElt *CTable, U32 symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81843d70)
Location: lib/zstd/compress/huf_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff81843d70-ffffffff81843d8a: HUF_getNbBitsFromCTable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
U32 HUF_getNbBitsFromCTable(const HUF_CElt *CTable, U32 symbolValue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/huf_compress.c (ffffffff81895930)
Location: lib/zstd/compress/huf_compress.c:270
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs
```
**Symbols:**

```
ffffffff81895930-ffffffff8189594a: HUF_getNbBitsFromCTable (STB_GLOBAL)
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
