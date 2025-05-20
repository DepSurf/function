# Function: <code>bdi_alloc</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253b3c)
Location: include/linux/backing-dev.h:36
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff81275bbc)
Location: include/linux/backing-dev.h:37
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff8129c136)
Location: include/linux/backing-dev.h:38
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812b1276)
Location: include/linux/backing-dev.h:38
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812cdd16)
Location: include/linux/backing-dev.h:38
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812df736)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277d20)
Location: mm/backing-dev.c:867
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:__blk_alloc_queue
```
**Symbols:**

```
ffffffff81277d20-ffffffff81277dd9: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81282330)
Location: mm/backing-dev.c:734
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue
```
**Symbols:**

```
ffffffff81282330-ffffffff81282408: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81287440)
Location: mm/backing-dev.c:733
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue
```
**Symbols:**

```
ffffffff81287440-ffffffff81287518: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6dc0)
Location: mm/backing-dev.c:806
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff812c6dc0-ffffffff812c6eba: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813242b0)
Location: mm/backing-dev.c:796
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff813242b0-ffffffff81324351: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81398bc0)
Location: mm/backing-dev.c:919
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff81398bc0-ffffffff81398c61: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cbb20)
Location: mm/backing-dev.c:932
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff813cbb20-ffffffff813cbbc1: bdi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f6470)
Location: mm/backing-dev.c:928
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff813f6470-ffffffff813f6540: bdi_alloc (STB_GLOBAL)
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
In fs/super.c (ffff800010386164)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f0b8)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
```
```
In drivers/mtd/mtdcore.c (c159c270)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:init_mtd
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
In fs/super.c (c00000000047c698)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffe000258c58)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812d7d16)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812c8996)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812d5b26)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
In fs/super.c (ffffffff812e6b36)
Location: include/linux/backing-dev.h:40
Inline: True
Inline callers:
  - fs/super.c:super_setup_bdi_name
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
