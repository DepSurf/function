# Function: <code>blk_queue_flag_clear</code>

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
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147d7f0)
Location: block/blk-core.c:94
Inline: False
Direct callers:
  - block/blk-core.c:blk_clear_preempt_only
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_flush_queueable
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8147d7f0-ffffffff8147d82a: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149b100)
Location: block/blk-core.c:86
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_flush_queueable
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8149b100-ffffffff8149b113: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814c9230)
Location: block/blk-core.c:87
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814c9230-ffffffff814c9243: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e2410)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814e2410-ffffffff814e2423: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815410d0)
Location: block/blk-core.c:92
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815410d0-ffffffff815410e3: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155dd60)
Location: block/blk-core.c:91
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8155dd60-ffffffff8155dd73: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815665c0)
Location: block/blk-core.c:92
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815665c0-ffffffff815665d3: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca9e0)
Location: block/blk-core.c:90
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815ca9e0-ffffffff815ca9f3: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675f20)
Location: block/blk-core.c:92
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-stat.c:blk_stat_disable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-zoned.c:blk_queue_clear_zone_settings
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81675f20-ffffffff81675f3b: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731f60)
Location: block/blk-core.c:90
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-stat.c:blk_stat_disable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-zoned.c:disk_clear_zone_settings
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81731f60-ffffffff81731f7b: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e370)
Location: block/blk-core.c:90
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_disable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-zoned.c:disk_clear_zone_settings
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8176e370-ffffffff8176e38e: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b0590)
Location: block/blk-core.c:91
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_stable_writes_store
  - block/blk-sysfs.c:queue_iostats_store
  - block/blk-sysfs.c:queue_random_store
  - block/blk-sysfs.c:queue_nonrot_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_disable_accounting
  - block/blk-stat.c:blk_stat_remove_callback
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_unregister
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817b0590-ffffffff817b05ab: blk_queue_flag_clear (STB_GLOBAL)
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0c90)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e0c90-ffff8000105e0ce8: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e19c)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c078e19c-c078e1bc: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007716f0)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c0000000007716f0-c000000000771734: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000421f32)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000421f32-ffffffe000421f82: blk_queue_flag_clear (STB_GLOBAL)
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da9f0)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814da9f0-ffffffff814daa03: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb3a0)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814cb3a0-ffffffff814cb3b3: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d6a80)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814d6a80-ffffffff814d6a93: blk_queue_flag_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ef690)
Location: block/blk-core.c:89
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-stat.c:blk_stat_remove_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:disable_discard
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814ef690-ffffffff814ef6a3: blk_queue_flag_clear (STB_GLOBAL)
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
