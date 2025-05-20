# Function: <code>bio_list_pop</code>

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
In block/bio.c (ffffffff813b034b)
Location: include/linux/bio.h:681
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff813b9cc9)
Location: include/linux/bio.h:681
Inline: True
```
```
In block/blk-throttle.c (ffffffff813d965c)
Location: include/linux/bio.h:681
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
```
```
In drivers/block/xen-blkfront.c (ffffffff81578485)
Location: include/linux/bio.h:681
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
```
```
In drivers/md/dm.c (ffffffff816a2c95)
Location: include/linux/bio.h:681
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
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
In block/bio.c (ffffffff813f3d9b)
Location: include/linux/bio.h:633
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff813fdaa7)
Location: include/linux/bio.h:633
Inline: True
```
```
In block/blk-throttle.c (ffffffff8141fa92)
Location: include/linux/bio.h:633
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdc18)
Location: include/linux/bio.h:633
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/md/dm.c (ffffffff81703519)
Location: include/linux/bio.h:633
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
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
In block/bio.c (ffffffff8140d61b)
Location: include/linux/bio.h:635
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814173e7)
Location: include/linux/bio.h:635
Inline: True
```
```
In block/blk-throttle.c (ffffffff8143c582)
Location: include/linux/bio.h:635
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa670)
Location: include/linux/bio.h:635
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff817353d9)
Location: include/linux/bio.h:635
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:flush_current_bio_list
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
In block/bio.c (ffffffff8141b2ef)
Location: include/linux/bio.h:654
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81425104)
Location: include/linux/bio.h:654
Inline: True
```
```
In block/blk-throttle.c (ffffffff8144b5bf)
Location: include/linux/bio.h:654
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff8160e8f3)
Location: include/linux/bio.h:654
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/md/dm.c (ffffffff8174e619)
Location: include/linux/bio.h:654
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
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
In block/bio.c (ffffffff81445f1f)
Location: include/linux/bio.h:658
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814501d3)
Location: include/linux/bio.h:658
Inline: True
```
```
In block/blk-throttle.c (ffffffff814760af)
Location: include/linux/bio.h:658
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff81677173)
Location: include/linux/bio.h:658
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/md/dm.c (ffffffff817c0644)
Location: include/linux/bio.h:658
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
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
In block/bio.c (ffffffff81478ea7)
Location: include/linux/bio.h:701
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81483420)
Location: include/linux/bio.h:701
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814aa683)
Location: include/linux/bio.h:701
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff816b3187)
Location: include/linux/bio.h:701
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/md/dm.c (ffffffff81808bae)
Location: include/linux/bio.h:701
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff81497107)
Location: include/linux/bio.h:663
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff8149ebea)
Location: include/linux/bio.h:663
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814c4ac2)
Location: include/linux/bio.h:663
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff816d43e9)
Location: include/linux/bio.h:663
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/md/dm.c (ffffffff81834c7e)
Location: include/linux/bio.h:663
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814c4a64)
Location: include/linux/bio.h:659
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814cccc5)
Location: include/linux/bio.h:659
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ef39c)
Location: include/linux/bio.h:659
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff814f326e)
Location: include/linux/bio.h:659
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff8170e6d2)
Location: include/linux/bio.h:659
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81877500)
Location: include/linux/bio.h:659
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814dd904)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814e5ef5)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150882c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff8150c80b)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff817329d2)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff818a9290)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff8153d2ac)
Location: include/linux/bio.h:650
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81545128)
Location: include/linux/bio.h:650
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81569b4c)
Location: include/linux/bio.h:650
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff8156e555)
Location: include/linux/bio.h:650
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff817edd6c)
Location: include/linux/bio.h:650
Inline: True
```
```
In drivers/md/dm.c (ffffffff819798c0)
Location: include/linux/bio.h:650
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81559dbc)
Location: include/linux/bio.h:652
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81561893)
Location: include/linux/bio.h:652
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff81584421)
Location: include/linux/bio.h:652
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81588235)
Location: include/linux/bio.h:652
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff8180269c)
Location: include/linux/bio.h:652
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197d492)
Location: include/linux/bio.h:652
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815626cc)
Location: include/linux/bio.h:655
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81569d17)
Location: include/linux/bio.h:655
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8158b215)
Location: include/linux/bio.h:655
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff815907c9)
Location: include/linux/bio.h:655
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff817e70cc)
Location: include/linux/bio.h:655
Inline: True
```
```
In drivers/md/dm.c (ffffffff81962202)
Location: include/linux/bio.h:655
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7bbb)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - block/bio.c:bioset_exit
  - block/bio.c:bio_put
  - block/bio.c:bio_cpu_dead
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff815cd698)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff815f0215)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff815f77c9)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff818770b8)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81a092e2)
Location: include/linux/bio.h:616
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816711cc)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81678d33)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff816a132b)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff816a6836)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff819bf2bf)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81b6fe9a)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172c96c)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81735773)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8176015b)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81765856)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff81b34a32)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81d0cd8f)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81768cec)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff81771ccc)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8179f28b)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff817a4919)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff81b87f0d)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81d75b4f)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817aad1c)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff817b400c)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff817e2d5b)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff817e84e6)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff81bdbdbd)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff81e2cc4f)
Location: include/linux/bio.h:637
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
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
In block/bio.c (ffff8000105db3f4)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffff8000105e34d4)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060cd38)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffff80001061050c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffff800010929e30)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffff800010aff6d0)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (c07875b0)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (c07907e0)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-cgroup.c (c07b62a8)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (c07ba798)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/md/dm.c (c0bdf678)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (c00000000076a444)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (c000000000776dd0)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a7c64)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (c0000000007addd8)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/md/dm.c (c000000000bee4ec)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffe00041d9a0)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffe000425068)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffe00044449c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffe00044822c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/md/dm.c (ffffffe0006ef650)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814d5ee4)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814de4d5)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81500e0c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81504deb)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff816f8985)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff8184f110)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814c6904)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814cee75)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f131c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff814f52a5)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/md/dm.c (ffffffff81816730)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814d1f74)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814da565)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814fce9c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81500e7b)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff81725e92)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff8189e740)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
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
In block/bio.c (ffffffff814eaa24)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_alloc_rescue
```
```
In block/blk-core.c (ffffffff814f3259)
Location: include/linux/bio.h:660
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81515f4c)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff815198f2)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/block/xen-blkfront.c (ffffffff817412e2)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/md/dm.c (ffffffff818bb070)
Location: include/linux/bio.h:660
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
```
</details>
</li>
</ul>

## Differences
