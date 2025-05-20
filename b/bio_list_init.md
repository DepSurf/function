# Function: <code>bio_list_init</code>

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
In block/bio.c (ffffffff813b0335)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:__bioset_create
```
```
In block/blk-core.c (ffffffff813b9c18)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-throttle.c (ffffffff813d948a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81577dae)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
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
In block/bio.c (ffffffff813f46ac)
Location: include/linux/bio.h:558
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff813fd9f8)
Location: include/linux/bio.h:558
Inline: True
```
```
In block/blk-throttle.c (ffffffff8141f9ec)
Location: include/linux/bio.h:558
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff815ce136)
Location: include/linux/bio.h:558
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8140e09c)
Location: include/linux/bio.h:560
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81417338)
Location: include/linux/bio.h:560
Inline: True
```
```
In block/blk-throttle.c (ffffffff8143c4dc)
Location: include/linux/bio.h:560
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff815facf4)
Location: include/linux/bio.h:560
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
```
In drivers/md/dm.c (ffffffff817339ca)
Location: include/linux/bio.h:560
Inline: True
Inline callers:
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
In block/bio.c (ffffffff8141bce3)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - block/bio.c:bioset_create
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81425070)
Location: include/linux/bio.h:579
Inline: True
```
```
In block/blk-throttle.c (ffffffff8144b520)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff8160eacd)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
```
In drivers/md/dm.c (ffffffff8174dc81)
Location: include/linux/bio.h:579
Inline: True
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
In block/bio.c (ffffffff81446993)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/bio.c:bioset_create
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81450140)
Location: include/linux/bio.h:583
Inline: True
```
```
In block/blk-throttle.c (ffffffff81476010)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff8167734d)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
```
In drivers/md/dm.c (ffffffff817bfd0a)
Location: include/linux/bio.h:583
Inline: True
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
In block/bio.c (ffffffff8147981b)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81483407)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814aa601)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff816af296)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8149787b)
Location: include/linux/bio.h:588
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8149ebcd)
Location: include/linux/bio.h:588
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814c4a3d)
Location: include/linux/bio.h:588
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff816d3ac6)
Location: include/linux/bio.h:588
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff814c521a)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814ccc38)
Location: include/linux/bio.h:584
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814efe9a)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff814f31e9)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff8170f596)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff814de12a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814e5e68)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150934a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff8150c789)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81733896)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8153eb34)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81545066)
Location: include/linux/bio.h:575
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156a5ad)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff8156cb06)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff817f0bf6)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8155b344)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8156156d)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8158500a)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81587576)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81805506)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff81563410)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81569cc9)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8158bba1)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff8158e3c6)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff817ea0b6)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff815c7d40)
Location: include/linux/bio.h:541
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff815cd67f)
Location: include/linux/bio.h:541
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff815f0f4e)
Location: include/linux/bio.h:541
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff815f40f3)
Location: include/linux/bio.h:541
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff818767e6)
Location: include/linux/bio.h:541
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff81672a78)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81678d21)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff816a2eb7)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff816a67c7)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff819be9a5)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8172e538)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff817351c1)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff81761485)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff817657e7)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81b340e5)
Location: include/linux/bio.h:534
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff8176a808)
Location: include/linux/bio.h:547
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8177173e)
Location: include/linux/bio.h:547
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8179fc27)
Location: include/linux/bio.h:547
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff817a48aa)
Location: include/linux/bio.h:547
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81b875e5)
Location: include/linux/bio.h:547
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff817acc68)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff817b3a7e)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff817e3729)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff817e8477)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81bdb495)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffff8000105da7d8)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffff8000105e3450)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060bfe4)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffff80001060ff30)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffff8000109282ec)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (c0787b40)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c07907a4)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-cgroup.c (c07b7a40)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (c07ba6f8)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
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
In block/bio.c (c00000000076ac6c)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c000000000776d24)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a8e58)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (c0000000007adcf0)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
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
In block/bio.c (ffffffe00041ddc8)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffe000424fd4)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000444e7a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffe00044817e)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
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
In block/bio.c (ffffffff814d670a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814de448)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150192a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81504d69)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff816f9896)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
```
In drivers/nvme/host/multipath.c (ffffffff8174a593)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
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
In block/bio.c (ffffffff814c70ca)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814cede8)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f1e3a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff814f5229)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/nvme/host/multipath.c (ffffffff8172c173)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
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
In block/bio.c (ffffffff814d279a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814da4d8)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814fd9ba)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81500df9)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff81726d56)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
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
In block/bio.c (ffffffff814eb2ba)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/bio.c:bioset_init
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814f31b8)
Location: include/linux/bio.h:585
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81516f7a)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In block/blk-throttle.c (ffffffff81519879)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In drivers/block/xen-blkfront.c (ffffffff817421a6)
Location: include/linux/bio.h:585
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
</ul>

## Differences
