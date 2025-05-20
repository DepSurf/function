# Function: <code>device_add_disk_no_queue_reg</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814985b0)
Location: block/genhd.c:721
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814985b0-ffffffff814985c2: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b2700)
Location: block/genhd.c:743
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814b2700-ffffffff814b2714: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0b70)
Location: block/genhd.c:758
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e0b70-ffffffff814e0b84: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f9fa0)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f9fa0-ffffffff814f9fb4: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155acc0)
Location: block/genhd.c:855
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8155acc0-ffffffff8155acd4: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81577000)
Location: block/genhd.c:774
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81577000-ffffffff81577014: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157efb0)
Location: block/genhd.c:575
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8157efb0-ffffffff8157efc4: device_add_disk_no_queue_reg (STB_GLOBAL)
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
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fba98)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff8000105fba98-ffff8000105fbad4: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a6ba0)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c07a6ba0-c07a6bc4: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000794de0)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c000000000794de0-c000000000794dfc: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000437b58)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe000437b58-ffffffe000437b8e: device_add_disk_no_queue_reg (STB_GLOBAL)
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
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f2580)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f2580-ffffffff814f2594: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e2ab0)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e2ab0-ffffffff814e2ac4: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ee610)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814ee610-ffffffff814ee624: device_add_disk_no_queue_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_add_disk_no_queue_reg(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815076b0)
Location: block/genhd.c:767
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff815076b0-ffffffff815076c4: device_add_disk_no_queue_reg (STB_GLOBAL)
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
