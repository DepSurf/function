# Function: <code>bdi_alloc_node</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e1770)
Location: mm/backing-dev.c:842
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811e1770-ffffffff811e1833: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f7790)
Location: mm/backing-dev.c:857
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811f7790-ffffffff811f7853: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218b90)
Location: mm/backing-dev.c:855
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff81218b90-ffffffff81218c53: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b910)
Location: mm/backing-dev.c:858
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff8122b910-ffffffff8122b9e1: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b580)
Location: mm/backing-dev.c:845
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff8123b580-ffffffff8123b653: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249aa0)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff81249aa0-ffffffff81249b79: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102df2a8)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffff8000102df2a8-ffff8000102df374: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0504114)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/mtd/mtdcore.c:init_mtd
```
**Symbols:**

```
c0504114-c05041d0: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039ed00)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
c00000000039ed00-c00000000039edf4: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f7078)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffe0001f7078-ffffffe0001f7128: bdi_alloc_node (STB_GLOBAL)
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
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812420f0)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff812420f0-ffffffff812421c9: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812350c0)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff812350c0-ffffffff81235199: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123fe90)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff8123fe90-ffffffff8123ff69: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct backing_dev_info *bdi_alloc_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f5f0)
Location: mm/backing-dev.c:868
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff8124f5f0-ffffffff8124f6c9: bdi_alloc_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
