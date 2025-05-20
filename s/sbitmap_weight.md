# Function: <code>sbitmap_weight</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81482310)
Location: lib/sbitmap.c:170
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_sysfs_show
  - block/blk-mq-tag.c:blk_mq_tag_sysfs_show
```
**Symbols:**

```
ffffffff81482310-ffffffff81482352: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b640)
Location: lib/sbitmap.c:204
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_show
```
**Symbols:**

```
ffffffff8148b640-ffffffff8148b682: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7760)
Location: lib/sbitmap.c:204
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_show
```
**Symbols:**

```
ffffffff814c7760-ffffffff814c77a2: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8440)
Location: lib/sbitmap.c:204
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_show
```
**Symbols:**

```
ffffffff814f8440-ffffffff814f8482: sbitmap_weight (STB_GLOBAL)
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
In lib/sbitmap.c (ffffffff8150c860)
Location: lib/sbitmap.c:284
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff8153af70)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff8155bd90)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff815e5880)
Location: lib/sbitmap.c:254
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff81609c40)
Location: lib/sbitmap.c:246
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815edac0)
Location: lib/sbitmap.c:332
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff815ece70-ffffffff815ece9d: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8165ab64)
Location: lib/sbitmap.c:332
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff81659d90-ffffffff81659dbd: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81772f64)
Location: lib/sbitmap.c:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff817729d0-ffffffff81772a05: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818a33a4)
Location: lib/sbitmap.c:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff818a2fe0-ffffffff818a3015: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818e56f4)
Location: lib/sbitmap.c:318
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff818e54c0-ffffffff818e54f5: sbitmap_weight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int sbitmap_weight(const struct sbitmap *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8192c6f4)
Location: lib/sbitmap.c:318
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_sysfs.c:sdev_show_device_busy
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
```
**Symbols:**

```
ffffffff8192c4c0-ffffffff8192c4f5: sbitmap_weight (STB_GLOBAL)
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
In lib/sbitmap.c (ffff8000106696c0)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (c08124d0)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (c00000000081f1b0)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffe000494a2e)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff81554380)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff81544600)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff815500c0)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
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
In lib/sbitmap.c (ffffffff81569f00)
Location: lib/sbitmap.c:271
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
