# Function: <code>ZSTD_decodeSequenceLong</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b35ee)
Location: lib/zstd/decompress.c:1253
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e6bf0)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff814e6bf0-ffffffff814e72b3: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fa8e0)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff814fa8e0-ffffffff814fafa3: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815280b0)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff815280b0-ffffffff81528799: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81548f40)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff81548f40-ffffffff81549629: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d4850)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff815d4850-ffffffff815d4f2c: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f24e0)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff815f24e0-ffffffff815f2bd6: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d4fd8)
Location: lib/zstd/decompress.c:1253
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff815d3570-ffffffff815d38a4: ZSTD_decodeSequenceLong.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8163fd9d)
Location: lib/zstd/decompress.c:1253
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff8163e110-ffffffff8163e598: ZSTD_decodeSequenceLong.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff8000106551f0)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffff8000106551f0-ffff800010655890: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c000000000805180)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
c000000000805180-c000000000805a08: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe0004829f8)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffe0004829f8-ffffffe00048316c: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81541520)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff81541520-ffffffff81541c09: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81531800)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff81531800-ffffffff81531ee9: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153d260)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff8153d260-ffffffff8153d949: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t *seqState, const unsigned int windowSize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81557090)
Location: lib/zstd/decompress.c:1253
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
**Symbols:**

```
ffffffff81557090-ffffffff81557779: ZSTD_decodeSequenceLong (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
