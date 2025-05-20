# Function: <code>ZSTD_safecopy</code>

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
void ZSTD_safecopy(BYTE *op, const BYTE * oend_w, const BYTE *ip, ptrdiff_t length, ZSTD_overlap_e ovtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755920)
Location: lib/zstd/decompress/zstd_decompress_block.c:720
Inline: False
```
**Symbols:**

```
ffffffff81755920-ffffffff81755b7e: ZSTD_safecopy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_safecopy(BYTE *op, const const BYTE * oend_w, const BYTE *ip, ptrdiff_t length, ZSTD_overlap_e ovtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81879550)
Location: lib/zstd/decompress/zstd_decompress_block.c:792
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
```
**Symbols:**

```
ffffffff81879550-ffffffff818797ae: ZSTD_safecopy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_safecopy(BYTE *op, const const BYTE * oend_w, const BYTE *ip, ptrdiff_t length, ZSTD_overlap_e ovtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818ba310)
Location: lib/zstd/decompress/zstd_decompress_block.c:792
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
```
**Symbols:**

```
ffffffff818ba310-ffffffff818ba5e8: ZSTD_safecopy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_safecopy(BYTE *op, const const BYTE * oend_w, const BYTE *ip, ptrdiff_t length, ZSTD_overlap_e ovtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190bed0)
Location: lib/zstd/decompress/zstd_decompress_block.c:792
Inline: False
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd
```
**Symbols:**

```
ffffffff8190bed0-ffffffff8190c1a8: ZSTD_safecopy (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const BYTE * oend_w</code> ➡️ <code>const const BYTE * oend_w</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
