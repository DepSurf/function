# Function: <code>ldm_parse_vblk</code>

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
In block/partitions/ldm.c (ffffffff813d01a0)
Location: block/partitions/ldm.c:1182
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff81415607)
Location: block/partitions/ldm.c:1130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff81430b37)
Location: block/partitions/ldm.c:1130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff8143dac1)
Location: block/partitions/ldm.c:1130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff81469e11)
Location: block/partitions/ldm.c:1130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff8149dcc7)
Location: block/partitions/ldm.c:1130
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814b802b)
Location: block/partitions/ldm.c:1127
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814e687d)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814ffc4d)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1113
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81560cb0-ffffffff81560df4: ldm_parse_vblk (STB_LOCAL)
ffffffff8156231f-ffffffff81562366: ldm_parse_vblk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1113
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff8157c7a0-ffffffff8157c8e4: ldm_parse_vblk (STB_LOCAL)
ffffffff81bf321c-ffffffff81bf3263: ldm_parse_vblk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1113
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81583fd0-ffffffff8158434b: ldm_parse_vblk (STB_LOCAL)
ffffffff81be50e9-ffffffff81be5130: ldm_parse_vblk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1113
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff815e97b0-ffffffff815e9b2b: ldm_parse_vblk (STB_LOCAL)
ffffffff81cd947d-ffffffff81cd94c4: ldm_parse_vblk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1104
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81699100-ffffffff8169947d: ldm_parse_vblk (STB_LOCAL)
ffffffff81e8cefe-ffffffff81e8cf45: ldm_parse_vblk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817584a0)
Location: block/partitions/ldm.c:1104
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff817584a0-ffffffff81758849: ldm_parse_vblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817959b0)
Location: block/partitions/ldm.c:1104
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff817959b0-ffffffff81795d57: ldm_parse_vblk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ldm_parse_vblk(const u8 *buf, int len, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d9310)
Location: block/partitions/ldm.c:1104
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff817d9310-ffffffff817d96b7: ldm_parse_vblk (STB_LOCAL)
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
In block/partitions/ldm.c (ffff8000106024cc)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (c07acd40)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (c00000000079c9d0)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffe00043d986)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814f822d)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814e873d)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff814f42bd)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
In block/partitions/ldm.c (ffffffff8150d31d)
Location: block/partitions/ldm.c:1113
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
