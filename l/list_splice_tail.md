# Function: <code>list_splice_tail</code>

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
In kernel/cgroup.c (ffffffff81115cb0)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
```
In fs/proc/kcore.c (ffffffff81286e73)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814d0491)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81636009)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff8171afe1)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff81734595)
Location: include/linux/list.h:305
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
In kernel/cgroup.c (ffffffff8111c9d2)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
```
In mm/shmem.c (ffffffff811bfe74)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff81218133)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/proc/kcore.c (ffffffff812b404c)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff813ee686)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81521615)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81696880)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff8178384d)
Location: include/linux/list.h:305
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817a066c)
Location: include/linux/list.h:305
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
In kernel/cgroup.c (ffffffff81124d02)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
```
```
In mm/shmem.c (ffffffff811d06f1)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff8122a6d3)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/proc/kcore.c (ffffffff812c98e4)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff81407ec6)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154db27)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c4760)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff817b0e01)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817cf26c)
Location: include/linux/list.h:318
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
In mm/shmem.c (ffffffff811d8ba3)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff812362f8)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff81285e72)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff812d6932)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff81415603)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81562103)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d8d41)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff817d1185)
Location: include/linux/list.h:318
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow.c (ffffffff817ee5fc)
Location: include/linux/list.h:318
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
In mm/shmem.c (ffffffff811ef2e8)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff81255138)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff812a88f2)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff812fb182)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff8143fdd3)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c640d)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81745471)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff8184b27a)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8120f16f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff81278f94)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff812cf482)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81328741)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff81472c37)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815febab)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81785f81)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81895677)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff81222311)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/huge_memory.c (ffffffff8128d644)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff812e47f2)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff8133f903)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814909b7)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619c7b)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ac9a1)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff818b72ea)
Location: include/linux/list.h:372
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff812318d0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81244db2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812a7fd0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff81302fe0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81367bf6)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814bdb4b)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164da2c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec015)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81903114)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8123f990)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81253272)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812b94c2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff81316060)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff8137fe76)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814d699b)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166ff2c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d4252)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181cee5)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81935eb4)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8126d948)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81281f4b)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812ee026)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8134fc32)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff813ca30a)
Location: include/linux/list.h:446
Inline: True
```
```
In crypto/drbg.c (ffffffff815365cb)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172057a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a1125)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ecaa4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81a0ad0f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8127803c)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8128c087)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812f9696)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8135c8ec)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff813dbfca)
Location: include/linux/list.h:464
Inline: True
```
```
In crypto/drbg.c (ffffffff8155353b)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173d4da)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aff05)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f5934)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81a0bf5f)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8106972c)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/shmem.c (ffffffff8127cd9c)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8128ec24)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812ffc64)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff813632b6)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff813e2f6c)
Location: include/linux/list.h:464
Inline: True
```
```
In crypto/drbg.c (ffffffff8155bcbb)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172105a)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189325a)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8f84)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff819f3151)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073e7c)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/backing-dev.c (ffffffff812c60b3)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/compaction.c (ffffffff812ceadb)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff813498b1)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff813b1ab6)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81434a7c)
Location: include/linux/list.h:464
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81477a73)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In crypto/drbg.c (ffffffff815bcfeb)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179fe7a)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81926dc2)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81974234)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81aa3fd2)
Location: include/linux/list.h:464
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810828fc)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/backing-dev.c (ffffffff81323528)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/compaction.c (ffffffff8132cc10)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff813c000f)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff81436b79)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff814aebd3)
Location: include/linux/list.h:473
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814f9ebd)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In crypto/drbg.c (ffffffff816669cb)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d97ab)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb3a3)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7d1a7)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad06a4)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81c1ca2e)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109538c)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/backing-dev.c (ffffffff81397d78)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/compaction.c (ffffffff813a31f0)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff814422fd)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff814c4bd9)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81545261)
Location: include/linux/list.h:473
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815946d1)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In crypto/drbg.c (ffffffff81720e0b)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2c27b)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/block/xen-blkfront.c (ffffffff81b308d3)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b804)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81dcdabe)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109831b)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/backing-dev.c (ffffffff813cacf8)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/compaction.c (ffffffff813d9cc0)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/migrate.c (ffffffff8146b55b)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff81477be9)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff814fa059)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff8157ce41)
Location: include/linux/list.h:473
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815cb6a5)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In crypto/drbg.c (ffffffff8175c6bb)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75a1b)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/block/xen-blkfront.c (ffffffff81b83dc3)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc2e84)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81e3e6bf)
Location: include/linux/list.h:473
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f8bb)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In mm/backing-dev.c (ffffffff813f5cd8)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/compaction.c (ffffffff814039fd)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/migrate.c (ffffffff8149a4fe)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff814a7369)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8152e79c)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff815b5761)
Location: include/linux/list.h:554
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81604442)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In crypto/drbg.c (ffffffff8179e5bb)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7c0b)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7cf3)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c90fb2)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c52a)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc8a84)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:flip_worker
  - drivers/gpu/drm/drm_flip_work.c:drm_flip_work_commit
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d77b84)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81efcf6f)
Location: include/linux/list.h:554
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffff8000102d1b74)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffff8000102ea85c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffff800010359c84)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffff8000103cca48)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffff80001044dae8)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffff8000105d2dc0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083aebc)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a547c8)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffff800010bd443c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/compaction.c (c050e004)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In fs/pnode.c (c05a877c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In crypto/drbg.c (c077fd1c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/usb/host/ehci-hcd.c (c0b29554)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (c0cefca4)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (c000000000391500)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (c0000000003ad464)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (c000000000443464)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (c0000000004ce468)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (c0000000005652bc)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (c00000000075f538)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b20598)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (c000000000cb34ac)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/compaction.c (ffffffe0001feef0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In fs/pnode.c (ffffffe000289f8e)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffe0002e234c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffe00041751a)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00067030e)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffe00075e342)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff81237fe0)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8124b8c2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812b1aa2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8130e640)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81378456)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814cef7b)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635fec)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d52c5)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff818d5e84)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8122b020)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff8123e862)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812a2e72)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff812ff250)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81368f26)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814bf99b)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e302)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In net/core/dev.c (ffffffff8188fcc2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff81235d80)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81249662)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812af8b2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8130c430)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff81375f26)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814cb00b)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663d6c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c90d2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811d65)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81926eb4)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
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
In mm/shmem.c (ffffffff8124605e)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81258ee2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
```
```
In mm/huge_memory.c (ffffffff812bfbf2)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In fs/pnode.c (ffffffff8131dc60)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/proc/kcore.c (ffffffff813899d6)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In crypto/drbg.c (ffffffff814e3adb)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167e32c)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e3372)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182c835)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In net/core/dev.c (ffffffff81948504)
Location: include/linux/list.h:432
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
</details>
</li>
</ul>

## Differences
