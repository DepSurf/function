# Function: <code>ZSTD_rescaleFreqs</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815bc73d)
Location: lib/zstd/zstd_opt.h:38
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e3518)
Location: lib/zstd/zstd_opt.h:38
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
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
void ZSTD_rescaleFreqs(const optState_t * optPtr, const const BYTE * src, const size_t srcSize, const int optLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:116
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
```
**Symbols:**

```
ffffffff81744a90-ffffffff81744f46: ZSTD_rescaleFreqs (STB_LOCAL)
ffffffff81ea3105-ffffffff81ea3213: ZSTD_rescaleFreqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_rescaleFreqs(const optState_t * optPtr, const const BYTE * src, const size_t srcSize, const int optLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:124
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff8185e700-ffffffff8185ed84: ZSTD_rescaleFreqs (STB_LOCAL)
ffffffff8208a5a8-ffffffff8208a6ce: ZSTD_rescaleFreqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_rescaleFreqs(const optState_t * optPtr, const const BYTE * src, const size_t srcSize, const int optLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:124
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff8189f2b0-ffffffff8189f8b0: ZSTD_rescaleFreqs (STB_LOCAL)
ffffffff8210a9ff-ffffffff8210ab25: ZSTD_rescaleFreqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_rescaleFreqs(const optState_t * optPtr, const const BYTE * src, const size_t srcSize, const int optLevel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (0)
Location: lib/zstd/compress/zstd_opt.c:124
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff818f0e70-ffffffff818f1470: ZSTD_rescaleFreqs (STB_LOCAL)
ffffffff821e8b6c-ffffffff821e8c92: ZSTD_rescaleFreqs.cold (STB_LOCAL)
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
