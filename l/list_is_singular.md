# Function: <code>list_is_singular</code>

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
In kernel/locking/rwsem-xadd.c (ffffffff8182308b)
Location: include/linux/list.h:229
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff810e8830)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_disable_func
```
```
In kernel/kprobes.c (ffffffff8112cf07)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_bottom
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In mm/mmap.c (ffffffff811c40f4)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In block/blk-mq.c (ffffffff813c6aaf)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In drivers/pci/pci.c (ffffffff81435619)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/char/virtio_console.c (ffffffff81516d8f)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81639f30)
Location: include/linux/list.h:229
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff8189dbd0)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/core.c (ffffffff810ef0b9)
Location: include/linux/list.h:229
Inline: True
```
```
In kernel/kprobes.c (ffffffff8113629b)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In mm/mmap.c (ffffffff811dffb4)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In block/blk-mq.c (ffffffff8140ac08)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In drivers/pci/pci.c (ffffffff81480f92)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/list.h:229
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81569a2e)
Location: include/linux/list.h:229
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169ac0b)
Location: include/linux/list.h:229
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff818d2a7d)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/core.c (ffffffff810f6229)
Location: include/linux/list.h:242
Inline: True
```
```
In kernel/kprobes.c (ffffffff8114001b)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In mm/mmap.c (ffffffff811eff04)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff81278ae0)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mount_busy
```
```
In block/blk-mq.c (ffffffff81425680)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In drivers/pci/pci.c (ffffffff814a2652)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/list.h:242
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff815962be)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c8ceb)
Location: include/linux/list.h:242
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff8190981a)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/patch.c (ffffffff810f885d)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/livepatch/transition.c (0)
Location: include/linux/list.h:242
Inline: True
```
```
In kernel/kprobes.c (ffffffff811413cb)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
```
In mm/mmap.c (ffffffff811fc480)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff81285abd)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff81310268)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff81433439)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
```
In drivers/pci/pci.c (ffffffff814ac3b3)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/list.h:242
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155e83e)
Location: include/linux/list.h:242
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff815aa0a5)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816dd6e7)
Location: include/linux/list.h:242
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fd10d)
Location: include/linux/list.h:242
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In kernel/locking/rwsem-xadd.c (ffffffff8199373f)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/patch.c (ffffffff81102a8d)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff811036ba)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/kprobes.c (ffffffff8114e26b)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
```
In mm/mmap.c (ffffffff812149c0)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff812a853d)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff81335148)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff8145f019)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/pci.c (ffffffff814eb483)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2b68)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81610a15)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81749e27)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81769c91)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/core.c (ffffffff817d5bb9)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/opp/debugfs.c (ffffffff817d65ab)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem-xadd.c (ffffffff819efd0d)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/patch.c (ffffffff8110b06d)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff8110bc50)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/kprobes.c (ffffffff8115cb9a)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In mm/mmap.c (ffffffff81235800)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff812cf0d9)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813633f8)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff81492939)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/pci.c (ffffffff8151a9d7)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb0c9)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8164a5a5)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81789dfc)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817aaeb6)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/core.c (ffffffff8181e85a)
Location: include/linux/list.h:243
Inline: True
```
```
In drivers/opp/debugfs.c (ffffffff8181f2a6)
Location: include/linux/list.h:243
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem-xadd.c (ffffffff81a2b73d)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/livepatch/patch.c (ffffffff8111685d)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff81117440)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
```
In kernel/kprobes.c (ffffffff8116986e)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In mm/mmap.c (ffffffff81249000)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff812e4449)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff8137b608)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814ac81e)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/pci.c (ffffffff81530737)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816162d9)
Location: include/linux/list.h:266
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81668795)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ada4c)
Location: include/linux/list.h:266
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d0f3c)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff8184b146)
Location: include/linux/list.h:266
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff810f8590)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff811209ae)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff81121674)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff8117671e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c37b0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In mm/compaction.c (ffffffff8124293d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff8125b2c2)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff81302c3e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813a5728)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814daace)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff814ec1ca)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff8156014d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815caebf)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81649f44)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8169e217)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec9f8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81810e78)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff8188e209)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff8110434c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8112d09e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff8112dc94)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff8118265d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cf195)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d77a4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d85c5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff81250dfd)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff812699c0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff81315cbe)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813be5a8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814f3e8e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff8150561a)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff8158127d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815ec13f)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166c3d4)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816c1247)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d4298)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181d8c8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81842069)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff818c0399)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff8110ef3d)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8113b707)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/livepatch/transition.c (ffffffff8113c246)
Location: include/linux/list.h:340
Inline: True
```
```
In kernel/kprobes.c (ffffffff811967ee)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb445)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f40c6)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f645b)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8127f4dd)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff8129a1f0)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff8134f699)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/io_uring.c (ffffffff8138480e)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
```
```
In fs/ext4/mballoc.c (ffffffff8140a5bd)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff815544b9)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff81565fda)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff81625cc0)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff81697cff)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c6a4)
Location: include/linux/list.h:340
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817749b7)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff81793005)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a11ea)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1f6d)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191626f)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff8199236d)
Location: include/linux/list.h:340
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff8110c124)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff81135ea7)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/livepatch/transition.c (ffffffff81136956)
Location: include/linux/list.h:358
Inline: True
```
```
In kernel/kprobes.c (ffffffff8119384e)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811e9595)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f2a76)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e3b)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8128957d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff812a5400)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff8135c541)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/io_uring.c (ffffffff813925d2)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_sq_thread
```
```
In fs/ext4/mballoc.c (ffffffff8141d559)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff81570bd8)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In block/blk-rq-qos.c (ffffffff81580f5a)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff8164bae0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff816b4e2f)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739664)
Location: include/linux/list.h:358
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8178f717)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff817bfa45)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818affe1)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fae8d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191d842)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff819955fd)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff81bb7476)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/locking/rwsem.c (ffffffff8110df5d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff81136ca7)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/livepatch/transition.c (ffffffff811377ae)
Location: include/linux/list.h:358
Inline: True
```
```
In kernel/kprobes.c (ffffffff8119481e)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea425)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f3906)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d2b)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8128ebe0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff812aaba0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff81363001)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/io_uring.c (ffffffff8139a2d8)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread
```
```
In fs/ext4/mballoc.c (ffffffff81423cca)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff81578b99)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In drivers/pci/pci.c (ffffffff8162e6b0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff81696ed7)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171ce12)
Location: include/linux/list.h:358
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817722a7)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff817a2c65)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189339f)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddc4d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81900043)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff8197a41a)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff81ba6443)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/sched/topology.c (ffffffff8111ec17)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/sched/topology.c:asym_cpu_capacity_scan
```
```
In kernel/locking/rwsem.c (ffffffff8112d5af)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8115999f)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff8115a459)
Location: include/linux/list.h:358
Inline: True
```
```
In kernel/kprobes.c (ffffffff811bd710)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_eprobe.c (ffffffff8120a3ba)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b265)
Location: include/linux/list.h:358
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81224bc6)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227e0b)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff812ceaa0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff812ec1c0)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff813b1801)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/io_uring.c (ffffffff813e9a3a)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_sq_thread
```
```
In fs/ext4/mballoc.c (ffffffff814776d4)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff815ddcc4)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_add_rq_to_plug
```
```
In drivers/pci/pci.c (ffffffff8169db6d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff8170cd80)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179bb84)
Location: include/linux/list.h:358
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817f8377)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff8182bfa5)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81926f62)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197976d)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199f7e3)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81a2342a)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff81c73e17)
Location: include/linux/list.h:358
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/sched/build_utility.c (ffffffff81143459)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/locking/rwsem.c (ffffffff81f2580f)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff81182f02)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/livepatch/transition.c (ffffffff81183e42)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/kprobes.c (ffffffff811f07dc)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_eprobe.c (ffffffff81246357)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a4f5)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81264a26)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812671b8)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8132cbe0)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff8134f0a1)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:can_vma_merge_before
```
```
In fs/pnode.c (ffffffff8143679b)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff814f9a34)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff8168ba39)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In io_uring/io_uring.c (ffffffff81e92083)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_sq_thread
```
```
In drivers/pci/pci.c (ffffffff817bf73d)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff8183b540)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5174)
Location: include/linux/list.h:368
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81936c87)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff8196cfa4)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7d43c)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6e69)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afcc96)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81b8c69a)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff81e176b9)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/sched/build_utility.c (ffffffff8116f871)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/locking/rwsem.c (ffffffff820d11f6)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff811bdf62)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
```
```
In kernel/livepatch/transition.c (ffffffff811bf077)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/kprobes.c (ffffffff812375ac)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293357)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa925)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812b6586)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9228)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff813a31c0)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff813c85f7)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In fs/pnode.c (ffffffff814c47db)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff81594254)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff8174a109)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In io_uring/io_uring.c (ffffffff8178f38b)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In io_uring/sqpoll.c (ffffffff8179a563)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/pci/pci.c (ffffffff818dbd1d)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff81970cb3)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a274e4)
Location: include/linux/list.h:368
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81a96b37)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/iommu/ioasid.c (ffffffff81ad7704)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61be9)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8b817)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81d2c04a)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff81fee3f9)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/sched/build_utility.c (ffffffff8117f6d1)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/locking/rwsem.c (ffffffff8215555b)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff811d0a6d)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff811d1932)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/kprobes.c (ffffffff8124e66c)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0516)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cd0f4)
Location: include/linux/list.h:368
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812d9a76)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc888)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df339)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
```
```
In mm/compaction.c (ffffffff813d6770)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff813fc7db)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In fs/pnode.c (ffffffff814f9c5b)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff815cb224)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff81786800)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In io_uring/io_uring.c (ffffffff817d06c0)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In io_uring/sqpoll.c (ffffffff817db5bc)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/pci/pci.c (ffffffff8191eded)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff819b7343)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a70c04)
Location: include/linux/list.h:368
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81ae2347)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8f85)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2367)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81d952da)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff8206a519)
Location: include/linux/list.h:368
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
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
In kernel/sched/build_utility.c (ffffffff8118cfd1)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/locking/rwsem.c (ffffffff8223839b)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff811e56bd)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff811e65b2)
Location: include/linux/list.h:449
Inline: True
```
```
In kernel/kprobes.c (ffffffff8126859c)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_eprobe.c (ffffffff812ccad6)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812eaae4)
Location: include/linux/list.h:449
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812f79d6)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa968)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd299)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
```
```
In mm/compaction.c (ffffffff81400440)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff814291b2)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:can_vma_merge_after
  - mm/mmap.c:can_vma_merge_before
```
```
In fs/pnode.c (ffffffff8152e4bb)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In block/blk-mq.c (ffffffff817c8ee0)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
```
In io_uring/io_uring.c (ffffffff81813ee3)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In io_uring/sqpoll.c (ffffffff8181f907)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In drivers/pci/pci.c (ffffffff81966f2c)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff81a018f3)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac2d04)
Location: include/linux/list.h:449
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81b35737)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7de65)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da7cd7)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81e4cdea)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In net/xdp/xsk.c (ffffffff8213dc69)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_tx_peek_release_desc_batch
  - net/xdp/xsk.c:__xsk_map_redirect
```
```
In net/mptcp/protocol.c (ffffffff8214ad7a)
Location: include/linux/list.h:449
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:__mptcp_close_ssk
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
In kernel/locking/rwsem.c (ffff800010169c28)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/kprobes.c (ffff8000101f7258)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffff80001024fa1c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffff800010257b10)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffff8000102588cc)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffff8000102e8020)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffff800010300e30)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffff8000103cc704)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffff800010495168)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffff8000105f3718)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffff800010607778)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476a94)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pci/pci.c (ffff8000106e41f0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722dd0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
```
```
In drivers/acpi/power.c (ffff800010777848)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffff80001083698c)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffff8000108b4440)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a579f0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a80f88)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffff800010b1ccd8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (c03b5d78)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/kprobes.c (c0437cb4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (c0482a60)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c048ac8c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c048b830)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (c050c068)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (c051f744)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (c05a8280)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (c0656c58)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (c079f84c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (c07b2954)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/bus/brcmstb_gisb.c (c154ebf0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pci/pci.c (c0880034)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/controller/pcie-rcar.c (c08afaec)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
```
```
In drivers/char/virtio_console.c (c09ae2ac)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (c0b2a758)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (c0b54440)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/usb/musb/musb_host.c (c0b6cb88)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
```
```
In drivers/opp/debugfs.c (c0bf743c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
```
In sound/core/pcm_native.c (c0c92450)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_unlink
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
In kernel/locking/rwsem.c (c0000000001c1a6c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (c0000000001f19b0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (c0000000001f2b80)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (c00000000026e668)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (c0000000002ed1ec)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c0000000002f9a50)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbc64)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (c0000000003a9fb8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (c0000000003cd0f0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (c0000000004cdebc)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (c0000000005be994)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (c00000000078b038)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (c0000000007a43b0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (c00000000085e648)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/char/virtio_console.c (c00000000094c540)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b256a4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (c000000000b5a1b0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (c000000000c0f6bc)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffe00010acea)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In mm/compaction.c (ffffffe0001fd9fa)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffe00020e2f8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffe000289be0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffe000319dc6)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffe000431d2a)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffe000442318)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffe0004bb4d6)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/char/virtio_console.c (ffffffe000565354)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000672df0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffe00069780e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffe000704c28)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff810fd65c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8112567e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff81126274)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff8117ac7d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c77b5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cfdc4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0be5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8124944d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff81262010)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff8130e29e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813b6b88)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814ec46e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff814fdbfa)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff8157579d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815db4b2)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632244)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81686c97)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/nvme/host/multipath.c (ffffffff81749ea7)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d5ca8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817fa419)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff81864ab9)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff810ed85c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff811180de)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff81118cd4)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff8116de1d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ba595)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811c2b94)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c39b5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff8123c3fd)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff81254430)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff812feeae)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813a7618)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814dc9be)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff814ee10a)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff81563efd)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815c6af2)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/acpi/nfit/core.c (ffffffff815f7eae)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
```
```
In drivers/char/virtio_console.c (ffffffff816648a7)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/nvme/host/multipath.c (ffffffff8172ba81)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/net/vxlan.c (ffffffff8176e486)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_fdb_delete
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e348)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817bf5b9)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff8182d769)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff810fa81c)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8112356e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff81124164)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff81178a4d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5585)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cdb94)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce9b5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff812471ed)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff8125fdb0)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff8130c08e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813b43e8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff814e84fe)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff814f9c8a)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff81574fcd)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815e041f)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660214)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816b4ff7)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c9118)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81812748)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81836ee9)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff818b5849)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In kernel/locking/rwsem.c (ffffffff811059e5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/livepatch/patch.c (ffffffff8112fb8e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
```
In kernel/livepatch/transition.c (ffffffff811307a4)
Location: include/linux/list.h:326
Inline: True
```
```
In kernel/kprobes.c (ffffffff8118631d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d37e5)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811dbdf4)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcc25)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In mm/compaction.c (ffffffff81256a1d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/mmap.c (ffffffff8126f780)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
```
```
In fs/pnode.c (ffffffff8131d8be)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/pnode.c:propagate_mount_busy
```
```
In fs/ext4/mballoc.c (ffffffff813c8ff7)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In block/blk-mq.c (ffffffff8150149e)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-rq-qos.c (ffffffff81512cea)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In drivers/pci/pci.c (ffffffff8158f59d)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/acpi/power.c (ffffffff815fa2df)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/acpi/power.c:__acpi_power_on
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167a80e)
Location: include/linux/list.h:326
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816cf7e7)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e33b8)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182d218)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81851279)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
```
In drivers/opp/debugfs.c (ffffffff818d1af9)
Location: include/linux/list.h:326
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
</details>
</li>
</ul>

## Differences
