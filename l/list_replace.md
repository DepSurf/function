# Function: <code>list_replace</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100e646)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104ebb0)
Location: include/linux/list.h:123
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81125a36)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81129e71)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8112b0b9)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff81189a47)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
```
```
In fs/exec.c (ffffffff8121351e)
Location: include/linux/list.h:123
Inline: True
```
```
In fs/xattr.c (ffffffff8123330f)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/xattr.c:__simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff812502f2)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy
```
```
In fs/ext4/page-io.c (ffffffff8129f9c0)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff813c1ce3)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8160d7f2)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff81710c4d)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8171ed32)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff81757d35)
Location: include/linux/list.h:123
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
In arch/x86/events/intel/cqm.c (ffffffff8100e346)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104ed4d)
Location: include/linux/list.h:123
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d994)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8113205d)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811332bc)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff8119c20d)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8123a07d)
Location: include/linux/list.h:123
Inline: True
```
```
In fs/xattr.c (ffffffff8125ba72)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff81279323)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
```
```
In fs/ext4/page-io.c (ffffffff812ce230)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff81405c83)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8166d3ae)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff8177857d)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff81787651)
Location: include/linux/list.h:123
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff817c3fd8)
Location: include/linux/list.h:123
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
In arch/x86/events/intel/cqm.c (ffffffff8100e406)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_destroy
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fc56)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050d83)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff811376c4)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8113bdbd)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113cff7)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811aba7d)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8124cdc8)
Location: include/linux/list.h:136
Inline: True
```
```
In fs/xattr.c (ffffffff8126f022)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8128cee3)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_list
```
```
In fs/ext4/page-io.c (ffffffff812e4020)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8141ff23)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8169b0ae)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff817a559d)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817b4c11)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff817f3af8)
Location: include/linux/list.h:136
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fcc9)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050f6e)
Location: include/linux/list.h:136
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81138c24)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8113d41b)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8113e61d)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811b2edd)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff81258df3)
Location: include/linux/list.h:136
Inline: True
```
```
In fs/xattr.c (ffffffff8127c831)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff812993a3)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff8131dc40)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8142dee3)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff816afded)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff817c37fd)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff817d37b1)
Location: include/linux/list.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
```
In net/ipv4/inetpeer.c (ffffffff81813ed8)
Location: include/linux/list.h:136
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053676)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054ac6)
Location: include/linux/list.h:137
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81145914)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8114a1e9)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8114b41d)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811c6b2d)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff8127af89)
Location: include/linux/list.h:137
Inline: True
```
```
In fs/xattr.c (ffffffff8129f2d1)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff812bc713)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff81342250)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff81459173)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8171ba1d)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/net_namespace.c (ffffffff8183d2bd)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffffffff8184dc81)
Location: include/linux/list.h:137
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105631a)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105789c)
Location: include/linux/list.h:137
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8115425c)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81158c5a)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8115a549)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
```
```
In kernel/padata.c (ffffffff811e7505)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812a268b)
Location: include/linux/list.h:137
Inline: True
```
```
In fs/xattr.c (ffffffff812c5e31)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff812e5476)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff813700f0)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff8148c656)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8175a9c2)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81898b10)
Location: include/linux/list.h:137
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810539aa)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810552a2)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff8116107c)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81165c1a)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81166b9c)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff811f8425)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In fs/exec.c (ffffffff812b727a)
Location: include/linux/list.h:137
Inline: True
```
```
In fs/xattr.c (ffffffff812db030)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff812fa0a6)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff81388580)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814a6286)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff8177ed02)
Location: include/linux/list.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff818baf70)
Location: include/linux/list.h:137
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056b42)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810584d8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff8116d720)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff811726f6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8117371c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81210945)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81a95aa4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812d4c72)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff812f96a1)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8131a7d6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/ext4/page-io.c (ffffffff813b2647)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814d4186)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/usb/core/hcd.c (ffffffff817bd362)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff819068e0)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810573f2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058da8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff811795c0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8117e5a6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8117f58c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff8121d4f5)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81acd387)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812e67f2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff8130b2d1)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8132d616)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81368824)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813cb697)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814ed4a6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81765ef9)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff817ed642)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81938fd0)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c6ae)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dbb4)
Location: include/linux/list.h:158
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8118bb02)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff811919f4)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81192bc5)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812497e5)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/shuffle.c (ffffffff81bc5d7e)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff8131e089)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff81344ab9)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff813673bf)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813b0ae6)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff814177ff)
Location: include/linux/list.h:158
Inline: True
```
```
In block/blk-softirq.c (ffffffff8154d083)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81826889)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff818bcbce)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:158
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105af20)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c254)
Location: include/linux/list.h:158
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81188d12)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8118eba4)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8118fd4d)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81254675)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812b380d)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff81c3ecde)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff81329599)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff81350da9)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8137471f)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813c20e6)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff8142b2ff)
Location: include/linux/list.h:158
Inline: True
```
```
In block/blk-mq.c (ffffffff8156be43)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - block/blk-mq.c:blk_done_softirq
```
```
In drivers/base/devres.c (ffffffff817d3ff5)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818373a9)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff818c98cf)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:158
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b8d0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cb56)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff8118a6b0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff8118f9d0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81190c79)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81258c15)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812b8eed)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff81c30dad)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff8132f3a9)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff81357a99)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8137b0cf)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff813c8ca6)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81431f10)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/base/devres.c (ffffffff817b7a05)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a559)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/usb/core/hcd.c (ffffffff818ad0cf)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:158
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064ee0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810661f6)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff811b3212)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff811b88b0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811b9b59)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81294835)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff812fb48d)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff81d4f6d3)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff8137cb89)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff813a5ec9)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff813c7d31)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff814194be)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81485760)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/base/devres.c (ffffffff8184117a)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4a99)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/usb/core/hcd.c (ffffffff8194216f)
Location: include/linux/list.h:158
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:158
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071910)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072e7f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/time/posix-timers.c (ffffffff811a892a)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff811e5662)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff811eb7d7)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811eccaa)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812e9a75)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff81362b8d)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff81f1f5f5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff813fbecf)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff8142a258)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff8144f5d1)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff81488ad0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8148ff56)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff81508c10)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/base/devres.c (ffffffff8198452f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee416)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a062)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:160
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081580)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082e4a)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/time/posix-timers.c (ffffffff811e872a)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff8122b6f2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81231bd7)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8123322a)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff813538b5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff813de55d)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff820c8853)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff81484f7f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff814dde61)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff8151c7a0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff81523aa6)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff815a3770)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/base/devres.c (ffffffff81af26cc)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b876)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e5d2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:160
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083ab0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810856fa)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/rcu/tree.c (ffffffff811cbe5f)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/time/posix-timers.c (ffffffff811fcd06)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff81241cd2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81248867)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81249ec1)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81384ab5)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff81412f6d)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff8214cad3)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff814b9eff)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81514691)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff815549a0)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff8155b1b1)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff815da200)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/base/devres.c (ffffffff81b40881)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbed96)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/usb/core/hcd.c (ffffffff81c854d2)
Location: include/linux/list.h:160
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:160
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c9f0)
Location: include/linux/list.h:241
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811ddb5f)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
```
```
In kernel/time/posix-timers.c (ffffffff81212ef6)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:exit_itimers
```
```
In kernel/auditfilter.c (ffffffff8125bae2)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81262746)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81263dd1)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff813adec5)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/vmalloc.c (ffffffff8143f9dd)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/shuffle.c (ffffffff8222f5e3)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff814ec47b)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/notify/mark.c (ffffffff81548b61)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/iomap/buffered-io.c (ffffffff8158ab90)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
```
In fs/quota/dquot.c (ffffffff815917f1)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/quota/dquot.c:quota_release_workfn
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/mballoc.c (ffffffff81603fee)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff816129c0)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f3af2)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:acpi_mipi_check_crs_csi2
```
```
In drivers/base/devres.c (ffffffff81b98721)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_krealloc
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c134e6)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca12e9)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
```
```
In drivers/usb/core/hcd.c (ffffffff81d39ed2)
Location: include/linux/list.h:241
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (0)
Location: include/linux/list.h:241
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
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffff8000101f3430)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffff8000101f457c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffff8000102a9bdc)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffff800010da0474)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffff80001038eac8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffff8000103bf6ac)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffff8000103e95f4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffff800010431360)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffff8000104a3714)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffff8000105ebfe8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966820)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffff800010a1c5ec)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffff800010bd78c8)
Location: include/linux/list.h:151
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
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (c043393c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c0434924)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (c04d7e18)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (c15be3f0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (c057503c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (c059c4f0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (c05c09cc)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (c05fb0fc)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (c06655b0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (c079842c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (c0a3cf18)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (c0af3f74)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (c0cf2984)
Location: include/linux/list.h:151
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
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (c000000000267f64)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (c0000000002694a4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (c00000000035cd30)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (c000000000eed194)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (c000000000485a24)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (c0000000004bdf30)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (c0000000004f00d8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (c0000000005457c0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (c0000000005d0618)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (c0000000007815c4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1da8c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (c000000000ad6614)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (c000000000cb78e4)
Location: include/linux/list.h:151
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
In kernel/auditfilter.c (ffffffe000162994)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffe000166916)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffe0001677f0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffe0001d2e6e)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffe000047786)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffe00025e58c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffe000280030)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffe00029e018)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffe0002ccc74)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffe000324fec)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffe00042bc0a)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2e32)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffe000640818)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffe000760eac)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056f72)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058928)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff81171be0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81176bc6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81177bac)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff81215b45)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81a6c1f7)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812dedd2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff813038b1)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff81325bf6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81360e04)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813c3c77)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814e5a86)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171a5e9)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff817a5a22)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff818d8fa0)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047162)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048aa8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff81164d80)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81169d66)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8116ad4c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812088a5)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81a2873e)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812ceef7)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff812f44d1)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff81316796)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81351aa4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813b46f7)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814d5fc0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f3a49)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff81797402)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81892de0)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810573a2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058d58)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff8116f9b0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81174996)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8117597c)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812138e5)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81ad8607)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812dcbe2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff813016a1)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff813236c6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff8135e8d4)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813c1107)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814e1b16)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817593b9)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff817e24c2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff81929fd0)
Location: include/linux/list.h:151
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058842)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a1f8)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
```
In kernel/auditfilter.c (ffffffff8117d1b0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_watch.c (ffffffff81182276)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811834bc)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/padata.c (ffffffff812228a5)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/shuffle.c (ffffffff81ae4ac2)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In fs/exec.c (ffffffff812ed98b)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/xattr.c (ffffffff813129e0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_set
```
```
In fs/notify/mark.c (ffffffff81335236)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_mark_destroy_workfn
```
```
In fs/quota/dquot.c (ffffffff81373774)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/ext4/page-io.c (ffffffff813d6267)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In block/blk-softirq.c (ffffffff814fa9d6)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_done_softirq
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81774899)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/usb/core/hcd.c (ffffffff817fc302)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In net/core/dev.c (ffffffff8194b6a0)
Location: include/linux/list.h:151
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
</details>
</li>
</ul>

## Differences
