# Function: <code>io_schedule</code>

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
In kernel/sched/wait.c (ffffffff81820bf6)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io
```
```
In fs/direct-io.c (ffffffff8124ba73)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In block/blk-core.c (ffffffff813b91a2)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-mq-tag.c (ffffffff813c72bc)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
```
```
In block/bsg.c (ffffffff813d6ab7)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/md/dm.c (ffffffff816a14df)
Location: include/linux/sched.h:431
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/wait.c (ffffffff8189b046)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io
```
```
In fs/direct-io.c (ffffffff81274920)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In block/blk-core.c (ffffffff813fcdfd)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-mq-tag.c (ffffffff8140b4ec)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_get
```
```
In block/bsg.c (ffffffff8141c792)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In drivers/md/dm.c (ffffffff8170258f)
Location: include/linux/sched.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
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
In kernel/sched/wait.c (ffffffff818cf676)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io
```
```
In mm/filemap.c (ffffffff811b10f6)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In fs/block_dev.c (ffffffff81283b6b)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81287d4b)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812b214d)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In block/blk-core.c (ffffffff81416782)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff81421ec3)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
```
```
In block/blk-mq-tag.c (ffffffff81425a92)
Location: include/linux/sched.h:466
Inline: True
```
```
In block/bsg.c (ffffffff81437cee)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-wbt.c (ffffffff8144aa0a)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In drivers/md/dm.c (ffffffff8173444c)
Location: include/linux/sched.h:466
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3140)
Location: kernel/sched/core.c:4993
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - block/blk-core.c:get_request
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff810b3140-ffffffff810b3179: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba540)
Location: kernel/sched/core.c:5038
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - block/blk-core.c:get_request
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff810ba540-ffffffff810ba579: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1bd0)
Location: kernel/sched/core.c:5163
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - block/blk-core.c:get_request
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/bsg.c:bsg_release
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff810c1bd0-ffffffff810c1c09: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810caf00)
Location: kernel/sched/core.c:5146
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff810caf00-ffffffff810caf39: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a989a0)
Location: kernel/sched/core.c:5599
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81a989a0-ffffffff81a989d9: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad02f0)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81ad02f0-ffffffff81ad0329: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc8940)
Location: kernel/sched/core.c:6023
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:wait_on_page_bit_common
  - mm/page_io.c:swap_readpage
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
**Symbols:**

```
ffffffff81bc8940-ffffffff81bc89ab: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c41710)
Location: kernel/sched/core.c:6843
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:wait_on_page_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
**Symbols:**

```
ffffffff81c41710-ffffffff81c4177d: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81c33680)
Location: kernel/sched/core.c:7194
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:wait_on_page_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81c33680-ffffffff81c336ed: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d51f80)
Location: kernel/sched/core.c:8392
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:wait_on_page_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81d51f80-ffffffff81d51fed: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f22560)
Location: kernel/sched/core.c:8683
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:bit_wait_io
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81f22560-ffffffff81f225d9: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cce00)
Location: kernel/sched/core.c:8867
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:bit_wait_io
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
**Symbols:**

```
ffffffff820cce00-ffffffff820cce79: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82151210)
Location: kernel/sched/core.c:9024
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:bit_wait_io
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
**Symbols:**

```
ffffffff82151210-ffffffff82151289: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82233fc0)
Location: kernel/sched/core.c:9019
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:bit_wait_io
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - block/blk-core.c:blk_io_schedule
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_bios_completion
```
**Symbols:**

```
ffffffff82233fc0-ffffffff82234039: io_schedule (STB_GLOBAL)
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
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da2088)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:wait_on_page_bit_common
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffff800010da2088-ffff800010da20c4: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e9a1f4)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
c0e9a1f4-c0e9a234: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee3500)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
c000000000ee3500-c000000000ee3550: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c578a)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffe0008c578a-ffffffe0008c57cc: io_schedule (STB_GLOBAL)
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
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6f160)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81a6f160-ffffffff81a6f199: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b590)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81a2b590-ffffffff81a2b5c9: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb570)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81adb570-ffffffff81adb5a9: io_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_schedule();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae7b10)
Location: kernel/sched/core.c:5790
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:bit_wait_io
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/page_io.c:swap_readpage
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-iocost.c:ioc_rqos_throttle
  - drivers/md/dm.c:dm_wait_for_completion
```
**Symbols:**

```
ffffffff81ae7b10-ffffffff81ae7b49: io_schedule (STB_GLOBAL)
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
