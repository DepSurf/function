# Function: <code>list_splice</code>

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
In mm/vmscan.c (ffffffff811a32a5)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slab_common.c (ffffffff811b32c1)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/slub.c (ffffffff811ee2ff)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8122cd7f)
Location: include/linux/list.h:293
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812350f6)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8123cf60)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81255287)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_scan_ready_list
```
```
In fs/proc/kcore.c (ffffffff81286da6)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff813653ce)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In block/blk-mq.c (ffffffff813c49fb)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814719ce)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff8154973a)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff8155a8bd)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad561)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8163164a)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff8171b008)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff81745edb)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/ipv4/inetpeer.c (ffffffff81757e8c)
Location: include/linux/list.h:293
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
In kernel/events/core.c (ffffffff81189a52)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811ba310)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff811ccd1e)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811cf0a6)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff8120d8ff)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8125550f)
Location: include/linux/list.h:293
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8125d829)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8126502b)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8127d627)
Location: include/linux/list.h:293
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812b3f7d)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff8139b199)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In block/blk-mq.c (ffffffff81408b1e)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814bfe6e)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff8159b38e)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff815ac8cb)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605419)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81644af3)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169221a)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff81783878)
Location: include/linux/list.h:293
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/inetpeer.c (ffffffff817c4135)
Location: include/linux/list.h:293
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
In kernel/events/core.c (ffffffff81198e22)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811ca9a0)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff811dce0e)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811df1d6)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff8121f956)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8126775f)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81270d49)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8127846d)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812911b7)
Location: include/linux/list.h:306
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812c9815)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff813b1e89)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In block/blk-mq.c (ffffffff8142368b)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814e1e5e)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff815c98ee)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff815db67b)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81634939)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81675bc3)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c02fa)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff817b0e2c)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/inetpeer.c (ffffffff817f3c4d)
Location: include/linux/list.h:306
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
In kernel/events/core.c (ffffffff811a0f02)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811d34f3)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff811e6066)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811e8e60)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff8122b1cc)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff81275eff)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8127e508)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8128578d)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8129e0af)
Location: include/linux/list.h:306
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812d6867)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff813c8479)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814edb4e)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff815de62e)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff815f020d)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff816499b1)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8168a2e0)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d4cba)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff817d11b0)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/inetpeer.c (ffffffff81814034)
Location: include/linux/list.h:306
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
In kernel/events/core.c (ffffffff811b4802)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811e8a49)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff811fc2a6)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811ff1c0)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff812468cc)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8129829f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812a0fe8)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812a820d)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812c15a2)
Location: include/linux/list.h:307
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812fb0b7)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff813ee909)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815226ce)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff81645653)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff8165770a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2bd1)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff816f3b0b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817413aa)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff8184b2a5)
Location: include/linux/list.h:307
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
In kernel/events/core.c (ffffffff811d397f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81209f60)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff8121dc9b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff812205d2)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff81269cbb)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812bdb5f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812c7bde)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812cedad)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812ea3ad)
Location: include/linux/list.h:307
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328677)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In security/smack/smackfs.c (ffffffff8141f9b3)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81558345)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff81680abb)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81693306)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff816eed3a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8173044d)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178263a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff8189569e)
Location: include/linux/list.h:307
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
In kernel/events/core.c (ffffffff811e3d4f)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8121cc45)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff81230c7b)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff81233612)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/slub.c (ffffffff8127e57b)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812d31cf)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812dcdde)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812e411d)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812ff581)
Location: include/linux/list.h:360
Inline: True
```
```
In security/smack/smackfs.c (ffffffff8143a7c8)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8156fcd5)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff816a054b)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff816b3986)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff817128aa)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81752b71)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817a8e7a)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff818b7311)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/ipv4/ip_input.c (ffffffff8191541e)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff819995d2)
Location: include/linux/list.h:360
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff811faf21)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8122d05e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff812410b4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff812439d0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff8129a37a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812f01d0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812fb4ae)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81302940)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81320728)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff8132e2ee)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8146842e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a01ab)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffff816d947a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff816ed6ff)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e21e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81792a07)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817e80f4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff8190313b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff8195f044)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81977950)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a05514)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff81207ff1)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8123b27e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff8124f559)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff81251e90)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812aa23a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff81301d70)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8130d2ce)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff813159c0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff813334d8)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff813417e5)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8148220e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c102b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff816db348)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816fd47a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff8171172f)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff817723ce)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817b6579)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81818fc4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff81935edb)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff819964e3)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819ae2e0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c0ed)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff81234cbb)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812682de)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff8127d69a)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - mm/slab_common.c:shutdown_memcg_caches
```
```
In mm/compaction.c (ffffffff812808a0)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812def50)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8133aeff)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81349b4f)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8134f14f)
Location: include/linux/list.h:434
Inline: True
```
```
In fs/eventpoll.c (ffffffff8136d7cb)
Location: include/linux/list.h:434
Inline: True
```
```
In security/smack/smackfs.c (ffffffff814da29b)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166b0ab)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff8178f618)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff817b6dd1)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff817cd345)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834961)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff8187d21c)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f0383)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81a0ad32)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff81a6ee5f)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81a8dd3c)
Location: include/linux/list.h:434
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068519)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
```
```
In kernel/events/core.c (ffffffff8123eccb)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81272d69)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff8128a970)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff812d0218)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff812ead20)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/migrate.c (ffffffff812f2313)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff81303631)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In fs/namespace.c (ffffffff81346bef)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81356a59)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8135bfff)
Location: include/linux/list.h:452
Inline: True
```
```
In fs/eventpoll.c (ffffffff8137ab5b)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff814f785b)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168b9fb)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff817ba1a8)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff817cbb01)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff817e1d0c)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81845341)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81c18c86)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f96a3)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81a0bf82)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff81a7782f)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81a97d0c)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068aab)
Location: include/linux/list.h:452
Inline: True
```
```
In kernel/events/core.c (ffffffff81242efb)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81278056)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff8128ffc4)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff812d6fe8)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff812f27d6)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/migrate.c (ffffffff812f867a)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff8130a778)
Location: include/linux/list.h:452
Inline: True
```
```
In fs/namespace.c (ffffffff8134d17f)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8135da69)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81362cb0)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff813816a0)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff814fecaa)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166e6d9)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff8179da06)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff817af471)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff817c611c)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff818283e1)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81c0aa09)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818dc482)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff819f3174)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff81a5fe87)
Location: include/linux/list.h:452
Inline: True
```
```
In net/netfilter/core.c (ffffffff81a8305c)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073821)
Location: include/linux/list.h:452
Inline: True
```
```
In kernel/events/core.c (ffffffff8127d74b)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812b5ced)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff812cfa61)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff8131ceb8)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff8133a208)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff81342d37)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff813553e4)
Location: include/linux/list.h:452
Inline: True
```
```
In fs/namespace.c (ffffffff8139b14f)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff813ac149)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff813b14b0)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff813ce8e0)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff81559cfa)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e28a9)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff81826a06)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff818386d1)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81850482)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b3d21)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81d0f958)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81977e92)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81aa3ff9)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow_offload.c (ffffffff81ad4623)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81b190a3)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81b3ccec)
Location: include/linux/list.h:452
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081c4e)
Location: include/linux/list.h:461
Inline: True
```
```
In kernel/events/core.c (ffffffff812d1d78)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8130ef6e)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff8132e49a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff81387558)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff813abf83)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff813b52c6)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff813c9bde)
Location: include/linux/list.h:461
Inline: True
```
```
In fs/namespace.c (ffffffff8141e99f)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8142d8b4)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff814363f0)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81457340)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff815f49d8)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180ce4a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff81965f87)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196aea4)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff8197ab14)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81995e25)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff819fecf5)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81a47d4a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad56e2)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81c1ca55)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow_offload.c (ffffffff81c52bc2)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81ca077a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81cc9198)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094686)
Location: include/linux/list.h:461
Inline: True
```
```
In kernel/events/core.c (ffffffff8133ab68)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8137cb9a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff813a4c3a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff814057b8)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff81429693)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff814355d3)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff8144ed63)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In fs/namespace.c (ffffffff814ab04f)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff814bb234)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff814c4410)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff814e6590)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff816a5458)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193b93a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff81acf717)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5384)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff81ae7a44)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81b069dc)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d335)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81bcee3a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c606d2)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81dcdae5)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow_offload.c (ffffffff81e08182)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81e5c77a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81e88d28)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097626)
Location: include/linux/list.h:461
Inline: True
```
```
In kernel/events/core.c (ffffffff8136ba48)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813aea33)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff813d6960)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/hugetlb.c (ffffffff81438cd8)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff8145ea1a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff8146b358)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff81484893)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In fs/namespace.c (ffffffff814dfe4f)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff814f0356)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff814f9800)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8151d100)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff816dde38)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197f93a)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff81b1ece7)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b34)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff81b3621e)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81b54a1c)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd10b5)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81c26aaa)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc7a92)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81e3e6e6)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow_offload.c (ffffffff81e7aaa2)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81eb9330)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81ee6c98)
Location: include/linux/list.h:461
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109eb96)
Location: include/linux/list.h:542
Inline: True
```
```
In kernel/events/core.c (ffffffff813946c8)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813d8098)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff81400640)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff8145d0ef)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/hugetlb.c (ffffffff81472695)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/migrate.c (ffffffff8149a2ee)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (ffffffff814b3d83)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In fs/fs-writeback.c (ffffffff81524a66)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8152e060)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff815516e0)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_done_scan
```
```
In security/smack/smackfs.c (ffffffff8171a95b)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff819cc0aa)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f3c3f)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:acpi_mipi_scan_crs_csi2
```
```
In drivers/iommu/iommu.c (ffffffff81b75326)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795a5)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In drivers/base/bus.c (ffffffff81b8dc3e)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff81bacfdc)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c25d25)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/gpu/drm/drm_modeset_helper.c (ffffffff81ccc661)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_helper.c:drm_helper_move_panel_connectors_to_head
```
```
In drivers/spi/spi.c (ffffffff81cd91ca)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7d012)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
```
```
In net/core/dev.c (ffffffff81efcf96)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/flow_offload.c (ffffffff81f3ac71)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81f7c480)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81faaaa8)
Location: include/linux/list.h:542
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
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
In kernel/events/core.c (ffff8000102942cc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffff8000102cc314)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffff8000102e597c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffff8000102e8930)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffff80001034bfb8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffff8000103b44bc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffff8000103c35d0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffff8000103cc3c8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffff8000103f0830)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffff800010401924)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffff8000105740e4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffff800010749ee8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffff8000108c72b8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffff8000108e93a0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffff800010901f88)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffff80001097759c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffff8000109c3ad0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a522d0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffff800010bd4464)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffff800010c42da0)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffff800010c5e7d8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffff800010cfcef0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (c04c26a0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (c04f60c0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (c0509c10)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (c050d6b0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (c054fdcc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (c0593870)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (c05a0fc0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (c05a7fbc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (c05c630c)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (c05d3890)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (c0727140)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (c08cc8f4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (c09be2b4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (c09d648c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (c09ec290)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (c0a4a158)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (c0ab18fc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (c0b24b38)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (c0cefcd0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (c0d5437c)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (c0d6de90)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (c0e04c3c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (c00000000033fb04)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (c00000000038979c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (c0000000003a7a7c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (c0000000003abb90)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (c00000000042b820)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (c0000000004b07d4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (c0000000004c13a8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (c0000000004cdaa0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (c0000000004f7f98)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (c00000000050b5d4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (c0000000006df360)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008ab3b4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (c00000000096da90)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (c00000000097eca8)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (c00000000099ffdc)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (c000000000a2fab0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (c000000000a89204)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1b954)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (c000000000cb34d4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (c000000000d3e924)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (c000000000d610f0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (c000000000e25380)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffe0001c4106)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffe0001eae18)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffe0001fc37c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffe0001fe6d4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffe00023d360)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffe000277c94)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffe000282262)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffe000289946)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffe0002a30f6)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffe0002adb0e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffe0003c72aa)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f8208)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffe00057c938)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de09c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffe000616dc2)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066e44a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffe00075e366)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffe0007b1d82)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffe0007c6ee2)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffe000847a4e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff81200611)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812338ce)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff81247ba9)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff8124a4e0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812a281a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812fa350)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff813058ae)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130dfa0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8132bab8)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff81339dc5)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8147a7ee)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b517b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff816a0d98)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816c2c6a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff816d7aaf)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81726abe)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8177b059)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d13a4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff818d5eab)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff81936353)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff8194e150)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff819db77d)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff811f3361)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81226948)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff8123ab53)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff8123d490)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812942ea)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812eaf70)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812f64ce)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812febb0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8131bc52)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff8132aaf5)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8146b20e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a3f7b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff8167e788)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff8169df1a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff816b210f)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ffeee)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8175ae09)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In net/core/dev.c (ffffffff8188fce9)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff818efe53)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81907c40)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8199853d)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff811fe3e1)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8123166e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff81245949)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff81248280)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812a062a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff812f8140)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8130369e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130bd90)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81329588)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff81337895)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8147688e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b570b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff816cf008)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816f113a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff817053ef)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff8176588e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817ab3f9)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8180de44)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff81926edb)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff819874e3)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819b8920)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a461fd)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/events/core.c (ffffffff8120d441)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81240aa0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff81254850)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff81257ab0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/compaction.c:split_map_pages
```
```
In mm/slub.c (ffffffff812b076a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff81309f60)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81314a0e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8131d5c0)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8133a907)
Location: include/linux/list.h:420
Inline: True
```
```
In fs/io_uring.c (ffffffff8134ac15)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_req
```
```
In security/smack/smackfs.c (ffffffff8148e33e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815cf17b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (ffffffff816e9578)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff8170b97a)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/power/main.c (ffffffff8171fd1c)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_lib.c (ffffffff81780f1e)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817c5389)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818284d4)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
```
```
In net/core/dev.c (ffffffff8194852b)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/sched/cls_api.c (ffffffff819a99a3)
Location: include/linux/list.h:420
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819c2197)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a51efb)
Location: include/linux/list.h:420
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
</details>
</li>
</ul>

## Differences
