# Function: <code>wb_put</code>

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
In mm/page-writeback.c (ffffffff8119a53a)
Location: include/linux/backing-dev-defs.h:220
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81227b46)
Location: include/linux/backing-dev-defs.h:220
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812381a3)
Location: include/linux/backing-dev-defs.h:220
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wbc_detach_inode
```
```
In fs/block_dev.c (ffffffff812486da)
Location: include/linux/backing-dev-defs.h:220
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In mm/page-writeback.c (ffffffff811aee4a)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81250276)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8126194e)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff81271110)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In mm/page-writeback.c (ffffffff811bf4fa)
Location: include/linux/backing-dev-defs.h:224
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81263316)
Location: include/linux/backing-dev-defs.h:224
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81274e4e)
Location: include/linux/backing-dev-defs.h:224
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff81284a7d)
Location: include/linux/backing-dev-defs.h:224
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In mm/page-writeback.c (ffffffff811c73b3)
Location: include/linux/backing-dev-defs.h:228
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81270b43)
Location: include/linux/backing-dev-defs.h:228
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8128239a)
Location: include/linux/backing-dev-defs.h:228
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812927a3)
Location: include/linux/backing-dev-defs.h:228
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff811dc1c3)
Location: include/linux/backing-dev-defs.h:253
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81293473)
Location: include/linux/backing-dev-defs.h:253
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812a4f0a)
Location: include/linux/backing-dev-defs.h:253
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812b55b3)
Location: include/linux/backing-dev-defs.h:253
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff811fd9f1)
Location: include/linux/backing-dev-defs.h:258
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812b90a3)
Location: include/linux/backing-dev-defs.h:258
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812cbdca)
Location: include/linux/backing-dev-defs.h:258
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812dcac3)
Location: include/linux/backing-dev-defs.h:258
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff81210511)
Location: include/linux/backing-dev-defs.h:260
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812ce1e3)
Location: include/linux/backing-dev-defs.h:260
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812e0cea)
Location: include/linux/backing-dev-defs.h:260
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff812f2043)
Location: include/linux/backing-dev-defs.h:260
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff8121fbb1)
Location: include/linux/backing-dev-defs.h:259
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812eb0a3)
Location: include/linux/backing-dev-defs.h:259
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812ff3fa)
Location: include/linux/backing-dev-defs.h:259
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff813139e3)
Location: include/linux/backing-dev-defs.h:259
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff8122d661)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812fcbe3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81314ac8)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff813268f3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff8125b240)
Location: include/linux/backing-dev-defs.h:280
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81335453)
Location: include/linux/backing-dev-defs.h:280
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8134e4aa)
Location: include/linux/backing-dev-defs.h:280
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff81360e23)
Location: include/linux/backing-dev-defs.h:280
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff812652b4)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81340dc3)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8135b358)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8136d10e)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff812694c3)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff813471b3)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff81361f58)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8137397e)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff812a5f3d)
Location: include/linux/backing-dev-defs.h:266
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff812c6065)
Location: include/linux/backing-dev-defs.h:266
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/inode.c (ffffffff81394c13)
Location: include/linux/backing-dev-defs.h:266
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff813b07cb)
Location: include/linux/backing-dev-defs.h:266
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/page-writeback.c (ffffffff812fec0d)
Location: include/linux/backing-dev-defs.h:261
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/backing-dev.c (ffffffff813234d5)
Location: include/linux/backing-dev-defs.h:261
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/inode.c (ffffffff81416fb5)
Location: include/linux/backing-dev-defs.h:261
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814355ba)
Location: include/linux/backing-dev-defs.h:261
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/page-writeback.c (ffffffff8136938a)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/backing-dev.c (ffffffff81397d25)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/inode.c (ffffffff814a25b5)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814c3627)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/page-writeback.c (ffffffff8139b52a)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/backing-dev.c (ffffffff813caca5)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/inode.c (ffffffff814d7715)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff814f8a0a)
Location: include/linux/backing-dev-defs.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/page-writeback.c (ffffffff813c549a)
Location: include/linux/backing-dev-defs.h:257
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In mm/backing-dev.c (ffffffff813f5c85)
Location: include/linux/backing-dev-defs.h:257
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/inode.c (ffffffff81509a25)
Location: include/linux/backing-dev-defs.h:257
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8152d269)
Location: include/linux/backing-dev-defs.h:257
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/page-writeback.c (ffff8000102bc4e8)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffff8000103acda4)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffff8000103ca9bc)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffff8000103e13cc)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (c04e8b24)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (c058dc7c)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c05a6f30)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (c05b9900)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (c0000000003749f4)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (c0000000004a857c)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c0000000004cc434)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (c0000000004e73b0)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffe0001df244)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffe000271bce)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffe000288b5c)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffe000297c0e)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff81225cb1)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812f51c3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130d0a8)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8131eed3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff81218e51)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812e5de3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff812fdcb8)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8130fa73)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff81223a51)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff812f2fd3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8130ae98)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8131c9a3)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In mm/page-writeback.c (ffffffff81232d46)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/inode.c (ffffffff81304903)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (ffffffff8131c5b6)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/block_dev.c (ffffffff8132ea81)
Location: include/linux/backing-dev-defs.h:282
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
</ul>

## Differences
