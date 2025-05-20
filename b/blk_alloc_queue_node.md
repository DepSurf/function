# Function: <code>blk_alloc_queue_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5820)
Location: block/blk-core.c:683
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
```
**Symbols:**

```
ffffffff813b5820-ffffffff813b5aba: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa690)
Location: block/blk-core.c:692
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813fa690-ffffffff813fa923: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414010)
Location: block/blk-core.c:693
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81414010-ffffffff814142a3: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421aa0)
Location: block/blk-core.c:813
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81421aa0-ffffffff81421d7c: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c5c0)
Location: block/blk-core.c:887
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8144c5c0-ffffffff8144c8aa: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f860)
Location: block/blk-core.c:997
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8147f860-ffffffff8147fbb4: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cca0)
Location: block/blk-core.c:474
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8149cca0-ffffffff8149cf0e: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cadf0)
Location: block/blk-core.c:472
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814cadf0-ffffffff814cb09a: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e3fd0)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e3fd0-ffffffff814e4282: blk_alloc_queue_node (STB_GLOBAL)
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
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0208)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff8000105e0208-ffff8000105e0470: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e488)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c078e488-c078e6e8: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007743a0)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c0000000007743a0-c0000000007746dc: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042373e)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe00042373e-ffffffe000423990: blk_alloc_queue_node (STB_GLOBAL)
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
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc5b0)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814dc5b0-ffffffff814dc862: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccf60)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814ccf60-ffffffff814cd212: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8640)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814d8640-ffffffff814d88f2: blk_alloc_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue_node(gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1250)
Location: block/blk-core.c:476
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f1250-ffffffff814f1502: blk_alloc_queue_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>spinlock_t *lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>spinlock_t *lock</code>
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
