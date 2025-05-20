# Function: <code>bio_list_add</code>

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
In block/bio.c (ffffffff813b036d)
Location: include/linux/bio.h:627
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff813b9be6)
Location: include/linux/bio.h:627
Inline: True
```
```
In block/blk-throttle.c (ffffffff813d9b45)
Location: include/linux/bio.h:627
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In drivers/md/dm.c (ffffffff816a0913)
Location: include/linux/bio.h:627
Inline: True
Inline callers:
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff813f3dbd)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff813fd9c6)
Location: include/linux/bio.h:579
Inline: True
```
```
In block/blk-throttle.c (ffffffff8141fa1b)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81701c63)
Location: include/linux/bio.h:579
Inline: True
Inline callers:
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff8140d63d)
Location: include/linux/bio.h:581
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81417306)
Location: include/linux/bio.h:581
Inline: True
```
```
In block/blk-throttle.c (ffffffff8143c50b)
Location: include/linux/bio.h:581
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff817339f0)
Location: include/linux/bio.h:581
Inline: True
Inline callers:
  - drivers/md/dm.c:flush_current_bio_list
  - drivers/md/dm.c:flush_current_bio_list
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff8141b301)
Location: include/linux/bio.h:600
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8142501a)
Location: include/linux/bio.h:600
Inline: True
```
```
In block/blk-throttle.c (ffffffff8144b54a)
Location: include/linux/bio.h:600
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff8174cbf3)
Location: include/linux/bio.h:600
Inline: True
Inline callers:
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff81445f31)
Location: include/linux/bio.h:604
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814500ea)
Location: include/linux/bio.h:604
Inline: True
```
```
In block/blk-throttle.c (ffffffff8147603a)
Location: include/linux/bio.h:604
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff817bedd3)
Location: include/linux/bio.h:604
Inline: True
Inline callers:
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff81478ef9)
Location: include/linux/bio.h:647
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81483451)
Location: include/linux/bio.h:647
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814aa624)
Location: include/linux/bio.h:647
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81808348)
Location: include/linux/bio.h:647
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff81497159)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8149ec1b)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-throttle.c (ffffffff814c4a67)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81834259)
Location: include/linux/bio.h:609
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814c4aad)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814cccdd)
Location: include/linux/bio.h:605
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f1856)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff814f3213)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff8187608a)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814dd950)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814e5f0d)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150ae46)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8150c7b0)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff818a7e8a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff8153d2d8)
Location: include/linux/bio.h:596
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81545141)
Location: include/linux/bio.h:596
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156bec6)
Location: include/linux/bio.h:596
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8156e4f9)
Location: include/linux/bio.h:596
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff81979a2c)
Location: include/linux/bio.h:596
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:dec_pending
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
In block/bio.c (ffffffff81559de8)
Location: include/linux/bio.h:598
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff815615cd)
Location: include/linux/bio.h:598
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff81586bd6)
Location: include/linux/bio.h:598
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff815881d9)
Location: include/linux/bio.h:598
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff8197e36d)
Location: include/linux/bio.h:598
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:dec_pending
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
In block/bio.c (ffffffff815626f8)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81569d30)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8158d8e6)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8159076e)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff81962120)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:dec_pending
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
In block/bio.c (ffffffff815c6418)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff815cd6b0)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff815f3356)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff815f776e)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff81a0b260)
Location: include/linux/bio.h:562
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:dm_io_dec_pending
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
In block/bio.c (ffffffff816711f8)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81678d6d)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff816a48f6)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff816a67e3)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In drivers/md/dm.c (ffffffff81b72e0b)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:dm_io_complete
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
In block/bio.c (ffffffff8172c998)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81735683)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff81763676)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81765803)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81d0fbcb)
Location: include/linux/bio.h:555
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__dm_io_complete
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
In block/bio.c (ffffffff81768d18)
Location: include/linux/bio.h:568
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81771c23)
Location: include/linux/bio.h:568
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8179ed8b)
Location: include/linux/bio.h:568
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff817a48c6)
Location: include/linux/bio.h:568
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81d79048)
Location: include/linux/bio.h:568
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__dm_io_complete
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
In block/bio.c (ffffffff817aad48)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff817b3f63)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff817e286b)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff817e8493)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff81e301b7)
Location: include/linux/bio.h:583
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__dm_io_complete
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
In block/bio.c (ffff8000105db414)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffff8000105e34f0)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e738)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffff800010610490)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffff800010afeaac)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (c07875f4)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c0790820)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-cgroup.c (c07b8f74)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (c07ba71c)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (c0bdd9f8)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (c00000000076a460)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c000000000776df0)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (c0000000007abc74)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (c0000000007add10)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (c000000000bec904)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffe00041d9b0)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffe000425078)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446c22)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffe00044819e)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffe0006ee368)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814d5f30)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814de4ed)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81503426)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81504d90)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/nvme/host/multipath.c (ffffffff81749d58)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff8184dd0a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814c6950)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814cee8d)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f38e6)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff814f5250)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b938)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff8181532a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814d1fc0)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814da57d)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ff4b6)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81500e20)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff8189d33a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
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
In block/bio.c (ffffffff814eaa70)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814f3271)
Location: include/linux/bio.h:606
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81518636)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff815198a0)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In drivers/md/dm.c (ffffffff818b969a)
Location: include/linux/bio.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:queue_io
```
</details>
</li>
</ul>

## Differences
