# Function: <code>ZSTD_execSequenceEndSplitLitBuffer</code>

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
size_t ZSTD_execSequenceEndSplitLitBuffer(BYTE *op, const BYTE * oend, const const BYTE * oend_w, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818798c0)
Location: lib/zstd/decompress/zstd_decompress_block.c:908
Inline: False
```
**Symbols:**

```
ffffffff818798c0-ffffffff818799e8: ZSTD_execSequenceEndSplitLitBuffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_execSequenceEndSplitLitBuffer(BYTE *op, const BYTE * oend, const const BYTE * oend_w, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818ba700)
Location: lib/zstd/decompress/zstd_decompress_block.c:908
Inline: False
```
**Symbols:**

```
ffffffff818ba700-ffffffff818ba828: ZSTD_execSequenceEndSplitLitBuffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_execSequenceEndSplitLitBuffer(BYTE *op, const BYTE * oend, const const BYTE * oend_w, seq_t sequence, const BYTE **litPtr, const const BYTE * litLimit, const const BYTE * prefixStart, const const BYTE * virtualStart, const const BYTE * dictEnd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190c2c0)
Location: lib/zstd/decompress/zstd_decompress_block.c:908
Inline: False
```
**Symbols:**

```
ffffffff8190c2c0-ffffffff8190c3e8: ZSTD_execSequenceEndSplitLitBuffer (STB_LOCAL)
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
