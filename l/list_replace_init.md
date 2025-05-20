# Function: <code>list_replace_init</code>

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
In kernel/auditfilter.c (ffffffff81125a36)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8112b0b9)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff81189a47)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
```
```
In fs/exec.c (ffffffff8121351e)
Location: include/linux/list.h:132
Inline: True
```
```
In fs/notify/mark.c (ffffffff812502f2)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy
```
```
In fs/ext4/page-io.c (ffffffff8129f9c0)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff813c1ce3)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8160d7f2)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff81710c4d)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8171ed32)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff81757d35)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
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
In kernel/auditfilter.c (ffffffff8112d994)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811332bc)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff8119c20d)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8123a07d)
Location: include/linux/list.h:132
Inline: True
```
```
In fs/notify/mark.c (ffffffff81279323)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
```
```
In fs/ext4/page-io.c (ffffffff812ce230)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff81405c83)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8166d3ae)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff8177857d)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81787651)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff817c3fd8)
Location: include/linux/list.h:132
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
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
In kernel/auditfilter.c (ffffffff811376c4)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8113cff7)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811aba7d)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8124cdc8)
Location: include/linux/list.h:145
Inline: True
```
```
In fs/notify/mark.c (ffffffff8128cee3)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
```
```
In fs/ext4/page-io.c (ffffffff812e4020)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8141ff23)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8169b0ae)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff817a559d)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817b4c11)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff817f3af8)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
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
In kernel/auditfilter.c (ffffffff81138c24)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8113e61d)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811b2edd)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff81258df3)
Location: include/linux/list.h:145
Inline: True
```
```
In fs/notify/mark.c (ffffffff812993a3)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff8131dc40)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8142dee3)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff816afded)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff817c37fd)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817d37b1)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff81813ed8)
Location: include/linux/list.h:145
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
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
In kernel/auditfilter.c (ffffffff81145914)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8114b41d)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811c6b2d)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8127af89)
Location: include/linux/list.h:146
Inline: True
```
```
In fs/notify/mark.c (ffffffff812bc713)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff81342250)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff81459173)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8171ba1d)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff8183d2bd)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8184dc81)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8115425c)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8115a549)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811e7505)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812a268b)
Location: include/linux/list.h:146
Inline: True
```
```
In fs/notify/mark.c (ffffffff812e546f)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff813700ec)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8148c653)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8175a9be)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81898b10)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8116107c)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81166b90)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff811f8425)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812b727a)
Location: include/linux/list.h:146
Inline: True
```
```
In fs/notify/mark.c (ffffffff812fa09f)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff8138857c)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814a6283)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8177ecfe)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff818baf70)
Location: include/linux/list.h:146
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8116d720)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81173710)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81210945)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812d4c72)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8131a7cf)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff813b2642)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814d4183)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817bd35e)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff819068d9)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff811795c0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8117f580)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff8121d4f5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812e67f2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8132d60f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81368818)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813cb692)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814ed4a3)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817ed63e)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81938fc9)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8118bb02)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81192bc5)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812497e5)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In fs/exec.c (ffffffff8131e089)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff813673bf)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813b0ae6)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff814177ff)
Location: include/linux/list.h:174
Inline: True
```
```
In block/blk-softirq.c (ffffffff8154d083)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff818bcbce)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff81188d12)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8118fd4d)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81254675)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812b380d)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff81329599)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8137471f)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813c20e6)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff8142b2ff)
Location: include/linux/list.h:174
Inline: True
```
```
In block/blk-mq.c (ffffffff8156be43)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - block/blk-mq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff818c98cf)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8118a6b0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81190c79)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81258c15)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812b8eed)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff8132f3a9)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8137b0cf)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813c8ca6)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81431f10)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff818ad0cf)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff811b3212)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811b9b59)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81294835)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812fb48d)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff8137cb89)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff813c7d31)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff814194be)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81485760)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff8194216f)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:174
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/time/posix-timers.c (ffffffff811a892a)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff811e5662)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811eccaa)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812e9a75)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff81362b8d)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff813fbecf)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8144f5d1)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff81488ad0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8148ff56)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81508c10)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a062)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/time/posix-timers.c (ffffffff811e872a)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff8122b6f2)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8123322a)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff813538b5)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff813de55d)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff81484f7f)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff814dde61)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff8151c7a0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff81523aa6)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff815a3770)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e5d2)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/rcu/tree.c (ffffffff811cbe5f)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/time/posix-timers.c (ffffffff811fcd06)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff81241cd2)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81249ec1)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81384ab5)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff81412f6d)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff814b9eff)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81514691)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff815549a0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8155b1b1)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff815da200)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff81c854d2)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:176
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/rcu/tree.c (ffffffff811ddb5f)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/time/posix-timers.c (ffffffff81212ef6)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff8125bae2)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81263dd1)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff813adec5)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff8143f9dd)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In fs/exec.c (ffffffff814ec47b)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81548b61)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff8158ab90)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff815917f1)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/mballoc.c (ffffffff81603fee)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff816129c0)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/usb/core/hcd.c (ffffffff81d39ed2)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:257
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffff8000101ee900)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffff8000101f4570)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffff8000102a9bd8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffff80001038eac8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffff8000103e95dc)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffff800010431350)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffff8000104a3710)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffff8000105ebfe8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffff800010a1c5e8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffff800010bd78c0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (c042e8f8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (c0434924)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (c04d7e18)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (c057503c)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (c05c09cc)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (c05fb0fc)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (c06655b0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (c079842c)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (c0af3f74)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (c0cf2984)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (c000000000261798)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (c0000000002694a4)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (c00000000035cd30)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (c000000000485a20)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (c0000000004f00c8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (c0000000005457c0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (c0000000005d0614)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (c0000000007815c4)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (c000000000ad6610)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (c000000000cb78e4)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffe00016298c)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffe0001677e8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffe0001d2e66)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffe00025e580)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffe00029e00e)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffe0002ccc70)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffe000324fe8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffe00042bc0a)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffe000640816)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffe000760ea2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff81171be0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81177ba0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81215b45)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812dedd2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81325bef)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81360df8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813c3c72)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814e5a83)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817a5a1e)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff818d8f99)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff81164d80)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8116ad40)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812088a5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812ceef7)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8131678f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81351a98)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813b46f2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814d5fbd)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817973fe)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81892dd9)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8116f9b0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81175970)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812138e5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812dcbe2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff813236bf)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff8135e8c8)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813c1102)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814e1b13)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817e24be)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81929fc9)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In kernel/auditfilter.c (ffffffff8117d1b0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811834b0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812228a5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812ed98b)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff8133522f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81373768)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813d6262)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814fa9d3)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817fc2fe)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff8194b699)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
</details>
</li>
</ul>

## Differences
