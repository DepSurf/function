# Function: <code>blk_freeze_queue_start</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430c30)
Location: block/blk-mq.c:86
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
```
**Symbols:**

```
ffffffff81430c30-ffffffff81430c6b: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ba30)
Location: block/blk-mq.c:122
Inline: True
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_freeze_queue
```
**Symbols:**

```
ffffffff8145ba30-ffffffff8145ba76: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e940)
Location: block/blk-mq.c:137
Inline: True
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_freeze_queue
```
**Symbols:**

```
ffffffff8148e940-ffffffff8148e986: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8260)
Location: block/blk-mq.c:143
Inline: True
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff814a8260-ffffffff814a82a3: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6ce0)
Location: block/blk-mq.c:145
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff814d6ce0-ffffffff814d6d54: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0060)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff814f0060-ffffffff814f00d4: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550530)
Location: block/blk-mq.c:131
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff81550530-ffffffff815505bf: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c950)
Location: block/blk-mq.c:135
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff8156c950-ffffffff8156c9dc: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574320)
Location: block/blk-mq.c:135
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_shared
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff81574320-ffffffff81574391: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8870)
Location: block/blk-mq.c:135
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff815d8870-ffffffff815d88e1: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685080)
Location: block/blk-mq.c:164
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff81685080-ffffffff816850fc: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81743000)
Location: block/blk-mq.c:164
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_start_drain
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff81743000-ffffffff8174307c: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e640)
Location: block/blk-mq.c:123
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_start_drain
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff8177e640-ffffffff8177e6bc: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0ce0)
Location: block/blk-mq.c:123
Inline: True
Direct callers:
  - block/blk-core.c:blk_queue_start_drain
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff817c0ce0-ffffffff817c0d5c: blk_freeze_queue_start (STB_GLOBAL)
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
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eefd0)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffff8000105eefd0-ffff8000105ef050: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b90c)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
c079b90c-c079b984: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785b10)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
c000000000785b10-c000000000785bc8: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e3ce)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffe00042e3ce-ffffffe00042e450: blk_freeze_queue_start (STB_GLOBAL)
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
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8640)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/nvme/host/core.c:nvme_start_freeze
  - drivers/nvme/host/multipath.c:nvme_mpath_start_freeze
```
**Symbols:**

```
ffffffff814e8640-ffffffff814e86b4: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8bb0)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/nvdimm/pmem.c:pmem_pagemap_kill
  - drivers/nvme/host/core.c:nvme_start_freeze
  - drivers/nvme/host/multipath.c:nvme_mpath_start_freeze
```
**Symbols:**

```
ffffffff814d8bb0-ffffffff814d8c24: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e46d0)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff814e46d0-ffffffff814e4744: blk_freeze_queue_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_freeze_queue_start(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fcb30)
Location: block/blk-mq.c:146
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_tag_set_depth
  - block/blk-pm.c:blk_pre_runtime_suspend
```
**Symbols:**

```
ffffffff814fcb30-ffffffff814fcba4: blk_freeze_queue_start (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
