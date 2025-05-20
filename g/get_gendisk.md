# Function: <code>get_gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813cab10)
Location: block/genhd.c:683
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff813cab10-ffffffff813cac0f: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140ede0)
Location: block/genhd.c:709
Inline: True
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff8140ede0-ffffffff8140eedf: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142a180)
Location: block/genhd.c:709
Inline: True
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff8142a180-ffffffff8142a27f: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81438440)
Location: block/genhd.c:721
Inline: True
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81438440-ffffffff81438514: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463ba0)
Location: block/genhd.c:782
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81463ba0-ffffffff81463cae: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497740)
Location: block/genhd.c:818
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81497740-ffffffff8149787b: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b1660)
Location: block/genhd.c:840
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff814b1660-ffffffff814b179b: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814dfa00)
Location: block/genhd.c:862
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff814dfa00-ffffffff814dfb37: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f8e30)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff814f8e30-ffffffff814f8f67: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155ad90)
Location: block/genhd.c:976
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff8155ad90-ffffffff8155aed9: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fa338)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffff8000105fa338-ffff8000105fa514: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5394)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
c07a5394-c07a54bc: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000793380)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
c000000000793380-c000000000793538: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe00043699c)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffe00043699c-ffffffe000436ad0: get_gendisk (STB_GLOBAL)
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
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f1410)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff814f1410-ffffffff814f1547: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1950)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff814e1950-ffffffff814e1a87: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed4a0)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff814ed4a0-ffffffff814ed5d7: get_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gendisk *get_gendisk(dev_t devt, int *partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815066b0)
Location: block/genhd.c:871
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - block/blk-cgroup.c:blkcg_conf_get_disk
```
**Symbols:**

```
ffffffff815066b0-ffffffff815067e7: get_gendisk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
