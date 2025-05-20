# Function: <code>part_to_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8100264b)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In block/bio.c (ffffffff813b060b)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff813b54c5)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff813c1935)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/genhd.c (ffffffff813cab98)
Location: include/linux/genhd.h:218
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81596a18)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:nd_iostat_end
```
```
In drivers/md/md.c (ffffffff816903f0)
Location: include/linux/genhd.h:218
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810026a9)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In block/bio.c (ffffffff813f4271)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff813fe714)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:part_round_stats
```
```
In block/blk-merge.c (ffffffff8140586d)
Location: include/linux/genhd.h:220
Inline: True
```
```
In block/genhd.c (ffffffff8140ee68)
Location: include/linux/genhd.h:220
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff815eba4a)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:__nd_iostat_start
  - drivers/nvdimm/core.c:__nd_iostat_start
```
```
In drivers/md/md.c (ffffffff816f10df)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810026c6)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
```
```
In block/bio.c (ffffffff8140dc61)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff814180f9)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:part_round_stats
```
```
In block/blk-merge.c (ffffffff8141fae6)
Location: include/linux/genhd.h:211
Inline: True
```
```
In block/genhd.c (ffffffff8142a208)
Location: include/linux/genhd.h:211
Inline: True
```
```
In drivers/md/md.c (ffffffff8172298a)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002608)
Location: include/linux/genhd.h:211
Inline: True
```
```
In block/bio.c (ffffffff8141b8c1)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff81425fa8)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:part_round_stats
```
```
In block/blk-merge.c (ffffffff8142d97b)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/genhd.c (ffffffff814384b3)
Location: include/linux/genhd.h:211
Inline: True
```
```
In drivers/md/md.c (ffffffff81739df4)
Location: include/linux/genhd.h:211
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002638)
Location: include/linux/genhd.h:214
Inline: True
```
```
In block/bio.c (ffffffff814464d3)
Location: include/linux/genhd.h:214
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff81451418)
Location: include/linux/genhd.h:214
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:part_round_stats
```
```
In block/genhd.c (ffffffff81463c18)
Location: include/linux/genhd.h:214
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff81465651)
Location: include/linux/genhd.h:214
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff817b0b43)
Location: include/linux/genhd.h:214
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002d6b)
Location: include/linux/genhd.h:215
Inline: True
```
```
In block/bio.c (ffffffff81479473)
Location: include/linux/genhd.h:215
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff81484688)
Location: include/linux/genhd.h:215
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:part_round_stats
```
```
In block/genhd.c (ffffffff814977d6)
Location: include/linux/genhd.h:215
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff81499363)
Location: include/linux/genhd.h:215
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff817f5443)
Location: include/linux/genhd.h:215
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002daf)
Location: include/linux/genhd.h:217
Inline: True
```
```
In block/bio.c (ffffffff81499de0)
Location: include/linux/genhd.h:217
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff8149f666)
Location: include/linux/genhd.h:217
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814b16f6)
Location: include/linux/genhd.h:217
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814b35a3)
Location: include/linux/genhd.h:217
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff81820fea)
Location: include/linux/genhd.h:217
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ed5)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814c7e7e)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814cd757)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814dfaa8)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814e1b34)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff818633f9)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ec5)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814e0f7e)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814e6a47)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814f8ed8)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814faee4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff8189513d)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003da7)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - init/do_mounts.c:devt_from_partuuid
```
```
In block/blk-core.c (ffffffff81543a46)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_start_io_acct
  - block/blk-core.c:disk_start_io_acct
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:update_io_ticks
```
```
In block/blk-flush.c (ffffffff81547f84)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff8154ae88)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
```
In block/genhd.c (ffffffff81559738)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/genhd.c:part_inflight_show
  - block/genhd.c:part_stat_show
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
```
```
In block/partitions/core.c (ffffffff8155d833)
Location: include/linux/genhd.h:220
Inline: True
Inline callers:
  - block/partitions/core.c:delete_partition
  - block/partitions/core.c:hd_struct_free
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff800010085534)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffff8000105ddba4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffff8000105e4274)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffff8000105fa41c)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffff8000105fce28)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffff800010ae81a8)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
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
In init/do_mounts.c (c0303ce0)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (c078af10)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (c0791578)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (c07a5430)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (c07a771c)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (c0bcb944)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000000010eac)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (c00000000076f4d4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (c000000000777fac)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (c000000000793468)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (c000000000796444)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (c000000000bd5cec)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffe0000b492c)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffe000420b32)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffe000425b0a)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffe000436a40)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffe000438afc)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffe0006dd6e6)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ec5)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814d955e)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814df027)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814f14b8)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814f34c4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff8183afbd)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810013a5)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814c9f0e)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814cf9c7)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814e19f8)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814e39d4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff8180262d)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002ec5)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814d55ee)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814db0b7)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff814ed548)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff814ef554)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff8188a5ed)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002f15)
Location: include/linux/genhd.h:224
Inline: True
```
```
In block/bio.c (ffffffff814ee1fc)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
```
```
In block/blk-core.c (ffffffff814f3ea9)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
```
```
In block/genhd.c (ffffffff81506758)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
  - block/genhd.c:get_gendisk
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/partition-generic.c (ffffffff815085e4)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - block/partition-generic.c:part_inflight_show
  - block/partition-generic.c:part_stat_show
```
```
In drivers/md/md.c (ffffffff818a9459)
Location: include/linux/genhd.h:224
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_make_request
```
</details>
</li>
</ul>

## Differences
