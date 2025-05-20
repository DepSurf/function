# Function: <code>ZSTD_buildSeqTable</code>

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
In lib/zstd/decompress.c (ffffffff814b291e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
  - lib/zstd/decompress.c:ZSTD_decompressSequencesLong
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814e782e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814fb51e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81528d02)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81549b92)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d5492)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
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
In lib/zstd/decompress.c (ffffffff815f316e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d458e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8163f38e)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff817556f0)
Location: lib/zstd/decompress/zstd_decompress_block.c:529
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff817556f0-ffffffff8175591a: ZSTD_buildSeqTable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8187a350)
Location: lib/zstd/decompress/zstd_decompress_block.c:605
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff8187a350-ffffffff8187a57b: ZSTD_buildSeqTable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff818bb1a0)
Location: lib/zstd/decompress/zstd_decompress_block.c:605
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff818bb1a0-ffffffff818bb3c0: ZSTD_buildSeqTable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff8190cd60)
Location: lib/zstd/decompress/zstd_decompress_block.c:605
Inline: True
Direct callers:
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress/zstd_decompress_block.c:ZSTD_decodeSeqHeaders
```
**Symbols:**

```
ffffffff8190cd60-ffffffff8190cf80: ZSTD_buildSeqTable.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff800010655da8)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0800748)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0000000008060c0)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000483a2c)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81542172)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81532452)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8153deb2)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81557ce2)
Location: lib/zstd/decompress.c:752
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
  - lib/zstd/decompress.c:ZSTD_decodeSeqHeaders
```
</details>
</li>
</ul>

## Differences
