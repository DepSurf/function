# Function: <code>__device_add_disk</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:657
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81498160-ffffffff8149858e: __device_add_disk (STB_LOCAL)
ffffffff81498e3c-ffffffff81498e64: __device_add_disk.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:676
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814b2280-ffffffff814b26d4: __device_add_disk (STB_LOCAL)
ffffffff814b2f7c-ffffffff814b2fa6: __device_add_disk.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814e06d0-ffffffff814e0b46: __device_add_disk (STB_LOCAL)
ffffffff814e1491-ffffffff814e1544: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814f9b00-ffffffff814f9f80: __device_add_disk (STB_LOCAL)
ffffffff814fa8e1-ffffffff814fa90b: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:777
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8155a9b0-ffffffff8155ac9b: __device_add_disk (STB_LOCAL)
ffffffff8155b8ae-ffffffff8155b8da: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:697
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81576d10-ffffffff81576fd4: __device_add_disk (STB_LOCAL)
ffffffff81bf28d1-ffffffff81bf28fd: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:498
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8157ec90-ffffffff8157ef85: __device_add_disk (STB_LOCAL)
ffffffff81be48b3-ffffffff81be48ef: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fb5f8)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffff8000105fb5f8-ffff8000105fba50: __device_add_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a6610)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
c07a6610-c07a6b80: __device_add_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c0000000007947d0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
c0000000007947d0-c000000000794dbc: __device_add_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe0004376f8)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffe0004376f8-ffffffe000437b1c: __device_add_disk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814f20e0-ffffffff814f2560: __device_add_disk (STB_LOCAL)
ffffffff814f2ec1-ffffffff814f2eeb: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814e2610-ffffffff814e2a90: __device_add_disk (STB_LOCAL)
ffffffff814e33d5-ffffffff814e33ff: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff814ee170-ffffffff814ee5f0: __device_add_disk (STB_LOCAL)
ffffffff814eef51-ffffffff814eef7b: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups, bool register_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:691
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk_no_queue_reg
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81507200-ffffffff8150768a: __device_add_disk (STB_LOCAL)
ffffffff81507fe3-ffffffff8150800d: __device_add_disk.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct attribute_group **groups</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, disk, register_queue</code> ➡️ <code>parent, disk, groups, register_queue</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
