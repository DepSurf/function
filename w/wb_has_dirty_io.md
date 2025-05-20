# Function: <code>wb_has_dirty_io</code>

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
In mm/page-writeback.c (ffffffff81198850)
Location: include/linux/backing-dev.h:43
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
  - mm/page-writeback.c:laptop_mode_timer_fn
```
```
In fs/fs-writeback.c (ffffffff81236185)
Location: include/linux/backing-dev.h:43
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wb_workfn
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
In mm/page-writeback.c (ffffffff811b067e)
Location: include/linux/backing-dev.h:44
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff812648f7)
Location: include/linux/backing-dev.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811c0c6e)
Location: include/linux/backing-dev.h:44
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff81277d37)
Location: include/linux/backing-dev.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811c8dcc)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - mm/page-writeback.c:laptop_mode_timer_fn
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff81284f6b)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811daae5)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff812a79fa)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811fc27f)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff812ce6f4)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8120ed2f)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff812e39f4)
Location: include/linux/backing-dev.h:52
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8121e92d)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8130219e)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8122c3cd)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff813152a6)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81259082)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8134ec92)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_io_list_del_locked
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
In mm/page-writeback.c (ffffffff81263572)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8135bb12)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_io_list_del_locked
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
In mm/page-writeback.c (ffffffff81268301)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff81362722)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_io_list_del_locked
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
In mm/page-writeback.c (ffffffff812a4f14)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/backing-dev.c (ffffffff812c601d)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/fs-writeback.c (ffffffff813b0f22)
Location: include/linux/backing-dev.h:53
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812fcedf)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/backing-dev.c (ffffffff81323492)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/fs-writeback.c (ffffffff81435db6)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8136731f)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/backing-dev.c (ffffffff81397ce2)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/fs-writeback.c (ffffffff814c3b70)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wb_io_lists_depopulated
  - fs/fs-writeback.c:wb_io_lists_populated
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
In mm/page-writeback.c (ffffffff8139999f)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/backing-dev.c (ffffffff813cac62)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/fs-writeback.c (ffffffff814f8f50)
Location: include/linux/backing-dev.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wb_io_lists_depopulated
  - fs/fs-writeback.c:wb_io_lists_populated
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
In mm/page-writeback.c (ffffffff813c379f)
Location: include/linux/backing-dev.h:50
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In mm/backing-dev.c (ffffffff813f5c42)
Location: include/linux/backing-dev.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In fs/fs-writeback.c (ffffffff8152d7b0)
Location: include/linux/backing-dev.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wb_io_lists_depopulated
  - fs/fs-writeback.c:wb_io_lists_populated
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
In mm/page-writeback.c (ffff8000102baf30)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffff8000103cb518)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (c04e65d8)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_update_write_bandwidth
```
```
In fs/fs-writeback.c (c05a78a8)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (c00000000037276c)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (c0000000004cd140)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_io_list_move_locked
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
In mm/page-writeback.c (ffffffe0001ddfba)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffe0002893a8)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81224a1d)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8130d886)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81217bcd)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff812fe496)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812227bd)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8130b676)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812312a0)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - mm/page-writeback.c:__wb_update_bandwidth
```
```
In fs/fs-writeback.c (ffffffff8131ce68)
Location: include/linux/backing-dev.h:57
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:wb_start_writeback
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
</details>
</li>
</ul>

## Differences
