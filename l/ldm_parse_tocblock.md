# Function: <code>ldm_parse_tocblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff813d1769)
Location: block/partitions/ldm.c:192
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81416cab)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814321db)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8143f0d0)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8146b52a)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
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
In block/partitions/ldm.c (ffffffff8149ef68)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
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
In block/partitions/ldm.c (ffffffff814b9310)
Location: block/partitions/ldm.c:140
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
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
In block/partitions/ldm.c (ffffffff814e70db)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffff815004ab)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff8155ff10-ffffffff81560001: ldm_parse_tocblock (STB_LOCAL)
ffffffff81561e36-ffffffff81561ea4: ldm_parse_tocblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff8157ba00-ffffffff8157baf1: ldm_parse_tocblock (STB_LOCAL)
ffffffff81bf2d33-ffffffff81bf2da1: ldm_parse_tocblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff81583620-ffffffff81583700: ldm_parse_tocblock (STB_LOCAL)
ffffffff81be4c8a-ffffffff81be4cfb: ldm_parse_tocblock.cold (STB_LOCAL)
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
In block/partitions/ldm.c (ffffffff815ea018)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff816999cf)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817575e0)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff817575e0-ffffffff81757768: ldm_parse_tocblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81794980)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff81794980-ffffffff81794b08: ldm_parse_tocblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ldm_parse_tocblock(const u8 *data, struct tocblock *toc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d82e0)
Location: block/partitions/ldm.c:126
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
**Symbols:**

```
ffffffff817d82e0-ffffffff817d8468: ldm_parse_tocblock (STB_LOCAL)
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
In block/partitions/ldm.c (ffff800010601c28)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (c07ad78c)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (c00000000079d6c4)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffe00043cec2)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffff814f8a8b)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffff814e8f9b)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffff814f4b1b)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
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
In block/partitions/ldm.c (ffffffff8150db7b)
Location: block/partitions/ldm.c:126
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
