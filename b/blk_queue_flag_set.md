# Function: <code>blk_queue_flag_set</code>

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
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147d7b0)
Location: block/blk-core.c:79
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-settings.c:blk_queue_flush_queueable
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
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
ffffffff8147d7b0-ffffffff8147d7ea: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149e786)
Location: block/blk-core.c:75
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
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
ffffffff8149b0e0-ffffffff8149b0f3: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb586)
Location: block/blk-core.c:76
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814c9210-ffffffff814c9223: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4776)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814e23f0-ffffffff814e2403: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815430f6)
Location: block/blk-core.c:81
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815410b0-ffffffff815410c3: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f94b)
Location: block/blk-core.c:80
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
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
ffffffff8155dd40-ffffffff8155dd53: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156808b)
Location: block/blk-core.c:81
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
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
ffffffff815665a0-ffffffff815665b3: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cce53)
Location: block/blk-core.c:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
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
ffffffff815ca9c0-ffffffff815ca9d3: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679193)
Location: block/blk-core.c:81
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81675f00-ffffffff81675f1b: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731f30)
Location: block/blk-core.c:79
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/genhd.c:del_gendisk
  - block/blk-iocost.c:ioc_qos_write
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81731f30-ffffffff81731f4b: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e340)
Location: block/blk-core.c:79
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/genhd.c:blk_mark_disk_dead
  - block/blk-iocost.c:ioc_qos_write
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8176e340-ffffffff8176e35e: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b0560)
Location: block/blk-core.c:80
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/blk-mq.c:blk_mq_quiesce_tagset
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/genhd.c:__blk_mark_disk_dead
  - block/blk-iocost.c:ioc_qos_write
  - block/mq-deadline.c:dd_init_sched
  - block/blk-integrity.c:blk_integrity_register
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817b0560-ffffffff817b057b: blk_queue_flag_set (STB_GLOBAL)
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
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0eac)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e0c38-ffff8000105e0c90: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e3d0)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c078e17c-c078e19c: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774278)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c0000000007716a0-c0000000007716e4: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042367c)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000421ee6-ffffffe000421f32: blk_queue_flag_set (STB_GLOBAL)
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
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcd56)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814da9d0-ffffffff814da9e3: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd706)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814cb380-ffffffff814cb393: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8de6)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814d6a60-ffffffff814d6a73: blk_queue_flag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f19f6)
Location: block/blk-core.c:78
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
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
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_quiesce_queue
  - block/blk-stat.c:blk_stat_enable_accounting
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-iocost.c:ioc_qos_write
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:__loop_update_dio
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/md/md.c:md_run
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814ef670-ffffffff814ef683: blk_queue_flag_set (STB_GLOBAL)
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
