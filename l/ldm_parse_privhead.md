# Function: <code>ldm_parse_privhead</code>

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
In block/partitions/ldm.c (ffffffff813d14bb)
Location: block/partitions/ldm.c:133
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
In block/partitions/ldm.c (ffffffff8141696f)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff81431e9f)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff8143edf2)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff8146b1e7)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff8149ec29)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff814b8fd1)
Location: block/partitions/ldm.c:81
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
In block/partitions/ldm.c (ffffffff814e74a0)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff81500870)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_privhead(const u8 *data, struct privhead *ph);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:67
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff8155fe20-ffffffff8155ff0c: ldm_parse_privhead (STB_LOCAL)
ffffffff81561d89-ffffffff81561e36: ldm_parse_privhead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ldm_parse_privhead(const u8 *data, struct privhead *ph);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:67
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
**Symbols:**

```
ffffffff8157b910-ffffffff8157b9fc: ldm_parse_privhead (STB_LOCAL)
ffffffff81bf2c86-ffffffff81bf2d33: ldm_parse_privhead.cold (STB_LOCAL)
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
In block/partitions/ldm.c (ffffffff81584ab4)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff815ea3d7)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff81699e2b)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff81759198)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff81796698)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff817da096)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool ldm_parse_privhead(const u8 *data, struct privhead *ph);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffff800010601fb0)
Location: block/partitions/ldm.c:67
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_partition
```
**Symbols:**

```
ffff800010601fb0-ffff80001060217c: ldm_parse_privhead (STB_LOCAL)
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
In block/partitions/ldm.c (c07adc9c)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (c00000000079dd2c)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffe00043d40c)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff814f8e50)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff814e9360)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff814f4ee0)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
In block/partitions/ldm.c (ffffffff8150df40)
Location: block/partitions/ldm.c:67
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_validate_privheads
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
<b>Arch</b>
<ul>
</ul>
