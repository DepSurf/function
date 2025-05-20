# Function: <code>blk_init_allocated_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *blk_init_allocated_queue(struct request_queue *q, request_fn_proc *rfn, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9820)
Location: block/blk-core.c:831
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813b9820-ffffffff813b990e: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *blk_init_allocated_queue(struct request_queue *q, request_fn_proc *rfn, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd5e0)
Location: block/blk-core.c:840
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff813fd5e0-ffffffff813fd6ff: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_queue *blk_init_allocated_queue(struct request_queue *q, request_fn_proc *rfn, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416f30)
Location: block/blk-core.c:841
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81416f30-ffffffff81417057: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_init_allocated_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424c10)
Location: block/blk-core.c:970
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81424c10-ffffffff81424d58: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_init_allocated_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d210)
Location: block/blk-core.c:1048
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8144d210-ffffffff8144d378: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_init_allocated_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480490)
Location: block/blk-core.c:1160
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81480490-ffffffff814805c8: blk_init_allocated_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>request_fn_proc *rfn</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t *lock</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct request_queue *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
