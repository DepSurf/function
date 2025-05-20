# Function: <code>ldm_parse_dsk3</code>

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
In block/partitions/ldm.c (ffffffff813d0204)
Location: block/partitions/ldm.c:925
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
In block/partitions/ldm.c (ffffffff81415a44)
Location: block/partitions/ldm.c:873
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
In block/partitions/ldm.c (ffffffff81430f74)
Location: block/partitions/ldm.c:873
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
In block/partitions/ldm.c (ffffffff8143e053)
Location: block/partitions/ldm.c:873
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
In block/partitions/ldm.c (ffffffff8146a3af)
Location: block/partitions/ldm.c:873
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
In block/partitions/ldm.c (ffffffff8149dfea)
Location: block/partitions/ldm.c:873
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
In block/partitions/ldm.c (ffffffff814b8097)
Location: block/partitions/ldm.c:870
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
In block/partitions/ldm.c (ffffffff814e68e6)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffff814ffcb6)
Location: block/partitions/ldm.c:856
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ldm_parse_dsk3(const u8 *buffer, int buflen, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81560a40)
Location: block/partitions/ldm.c:856
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
**Symbols:**

```
ffffffff81560a40-ffffffff81560b12: ldm_parse_dsk3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ldm_parse_dsk3(const u8 *buffer, int buflen, struct vblk *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8157c530)
Location: block/partitions/ldm.c:856
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
**Symbols:**

```
ffffffff8157c530-ffffffff8157c602: ldm_parse_dsk3 (STB_LOCAL)
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
In block/partitions/ldm.c (ffffffff815840d3)
Location: block/partitions/ldm.c:856
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
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
In block/partitions/ldm.c (ffffffff815e98b3)
Location: block/partitions/ldm.c:856
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
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
In block/partitions/ldm.c (ffffffff81699209)
Location: block/partitions/ldm.c:849
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81758554)
Location: block/partitions/ldm.c:849
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81795b48)
Location: block/partitions/ldm.c:849
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d94a8)
Location: block/partitions/ldm.c:849
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_parse_vblk
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
In block/partitions/ldm.c (ffff800010602538)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (c07ad14c)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (c00000000079cee0)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffe00043dbe2)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffff814f8296)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffff814e87a6)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffff814f4326)
Location: block/partitions/ldm.c:856
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
In block/partitions/ldm.c (ffffffff8150d386)
Location: block/partitions/ldm.c:856
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
</ul>
