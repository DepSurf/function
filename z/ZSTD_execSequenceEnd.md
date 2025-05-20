# Function: <code>ZSTD_execSequenceEnd</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755b80)
Location: lib/zstd/decompress/zstd_decompress_block.c:765
Inline: True
```
**Symbols:**

```
ffffffff81755b80-ffffffff81755cc6: ZSTD_execSequenceEnd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_execSequenceEnd(BYTE *op, const BYTE * oend, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81879a00)
Location: lib/zstd/decompress/zstd_decompress_block.c:861
Inline: False
```
**Symbols:**

```
ffffffff81879a00-ffffffff81879b42: ZSTD_execSequenceEnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_execSequenceEnd(BYTE *op, const BYTE * oend, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818ba840)
Location: lib/zstd/decompress/zstd_decompress_block.c:861
Inline: False
```
**Symbols:**

```
ffffffff818ba840-ffffffff818ba982: ZSTD_execSequenceEnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_execSequenceEnd(BYTE *op, const BYTE * oend, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190c400)
Location: lib/zstd/decompress/zstd_decompress_block.c:861
Inline: False
```
**Symbols:**

```
ffffffff8190c400-ffffffff8190c542: ZSTD_execSequenceEnd (STB_LOCAL)
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
