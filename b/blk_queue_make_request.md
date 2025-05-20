# Function: <code>blk_queue_make_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be290)
Location: block/blk-settings.c:158
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/block/brd.c:brd_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813be290-ffffffff813be3d5: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402210)
Location: block/blk-settings.c:158
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/block/brd.c:brd_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81402210-ffffffff81402355: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141be70)
Location: block/blk-settings.c:162
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8141be70-ffffffff8141bfc9: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429e70)
Location: block/blk-settings.c:162
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81429e70-ffffffff81429f63: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814550b0)
Location: block/blk-settings.c:163
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814550b0-ffffffff814551a3: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814884a0)
Location: block/blk-settings.c:163
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814884a0-ffffffff81488593: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2150)
Location: block/blk-settings.c:109
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814a2150-ffffffff814a2225: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0230)
Location: block/blk-settings.c:110
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff814d0230-ffffffff814d0305: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e95a0)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e95a0-ffffffff814e966b: blk_queue_make_request (STB_GLOBAL)
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
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7688)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff8000105e7688-ffff8000105e7718: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c07941b4)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c07941b4-c0794250: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c010)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c00000000077c010-c00000000077c0ac: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428426)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe000428426-ffffffe0004284b8: blk_queue_make_request (STB_GLOBAL)
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
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1b80)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e1b80-ffffffff814e1c4b: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2510)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814d2510-ffffffff814d25db: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddc10)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814ddc10-ffffffff814ddcdb: blk_queue_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue *q, make_request_fn *mfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6a70)
Location: block/blk-settings.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f6a70-ffffffff814f6b3b: blk_queue_make_request (STB_GLOBAL)
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
