# Function: <code>sg_free_table_chained</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81461d90)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81461d90-ffffffff81461dba: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff814808d0)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff814808d0-ffffffff814808fa: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81489b6f)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81489bc0-ffffffff81489beb: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff814c5cbf)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff814c5d10-ffffffff814c5d3b: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff814f6b00)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff814f6b00-ffffffff814f6b2a: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, bool first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8150af40)
Location: lib/sg_pool.c:79
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff8150af40-ffffffff8150af6a: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81539751)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81539780-ffffffff815397aa: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8155a571)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff8155a5a0-ffffffff8155a5ca: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815e3e31)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff815e3eb0-ffffffff815e3eda: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81608361)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff816083e0-ffffffff8160840a: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815eafc1)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff815eb040-ffffffff815eb067: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81657591)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81657450-ffffffff8165747b: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8176ee8a)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff8176ecf0-ffffffff8176ed3d: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8189e7ea)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff8189e620-ffffffff8189e66d: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff818e0dba)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff818e0bf0-ffffffff818e0c3d: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8192792a)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff81927760-ffffffff819277ad: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffff800010667870)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffff800010667898-ffff8000106678d0: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (c0810000)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
c0810028-c0810060: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (c00000000081cc60)
Location: lib/sg_pool.c:84
Inline: True
Inline callers:
  - lib/sg_pool.c:sg_alloc_table_chained
  - lib/sg_pool.c:sg_alloc_table_chained
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
c00000000081cd70-c00000000081cde8: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffe000492e8c)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffe000492eb4-ffffffe000492f06: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81552b51)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81552b80-ffffffff81552baa: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81542e31)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81542e60-ffffffff81542e8a: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8154e891)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff8154e8c0-ffffffff8154e8ea: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sg_free_table_chained(struct sg_table *table, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815686e1)
Location: lib/sg_pool.c:84
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
```
**Symbols:**

```
ffffffff81568710-ffffffff8156873a: sg_free_table_chained (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nents_first_chunk</code>
</li>
<li>
<b>Param removed. </b>
<code>bool first_chunk</code>
</li>
</ul>
</details>
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
