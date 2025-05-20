# Function: <code>flush_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098dc0)
Location: kernel/workqueue.c:2481
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_post_attach_flush
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_put_super
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_open
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:__dm_suspend
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff81098dc0-ffffffff8109938d: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c3a0)
Location: kernel/workqueue.c:2577
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_put_super
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff8109c3a0-ffffffff8109c900: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a14e0)
Location: kernel/workqueue.c:2579
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_put_super
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
```
**Symbols:**

```
ffffffff810a14e0-ffffffff810a1a5c: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e8b0)
Location: kernel/workqueue.c:2578
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_put_super
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
```
**Symbols:**

```
ffffffff8109e8b0-ffffffff8109ec95: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5120)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_put_super
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810a5120-ffffffff810a54d9: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab380)
Location: kernel/workqueue.c:2643
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810ab380-ffffffff810ab761: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b4400)
Location: kernel/workqueue.c:2666
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810b4400-ffffffff810b47e1: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2762
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810bef5a-ffffffff810bef6d: flush_workqueue.cold (STB_LOCAL)
ffffffff810b9fd0-ffffffff810ba3e7: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0450)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810c0450-ffffffff810c086e: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7be0)
Location: kernel/workqueue.c:2768
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810c7be0-ffffffff810c7fde: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2d00)
Location: kernel/workqueue.c:2774
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810c2d00-ffffffff810c30fe: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4b10)
Location: kernel/workqueue.c:2775
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810c4b10-ffffffff810c4f26: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2814
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/io-pgfault.c:iopf_queue_flush_dev
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff81ca5144-ffffffff81ca5159: flush_workqueue.cold (STB_LOCAL)
ffffffff810d7750-ffffffff810d7b20: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011ce30)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:kvm_irqfd_release
  - virt/kvm/eventfd.c:kvm_irqfd
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffff80001011ce30-ffff80001011d268: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0372e68)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
c0372e68-c037344c: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000167040)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
c000000000167040-c000000000167534: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d74a4)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffe0000d74a4-ffffffe0000d7766: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ba7c0)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/nvme/host/pci.c:nvme_exit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810ba7c0-ffffffff810babde: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9100)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/nfit/core.c:__acpi_nfit_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_shutdown
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/nvme/host/pci.c:nvme_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810a9100-ffffffff810a951e: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9d20)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810b9d20-ffffffff810ba13e: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2d20)
Location: kernel/workqueue.c:2771
Inline: False
Direct callers:
  - kernel/workqueue.c:drain_workqueue
  - kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_post_attach
  - mm/slab_common.c:kmem_cache_destroy
  - fs/fs-writeback.c:cgroup_writeback_umount
  - fs/io_uring.c:io_destruct_skb
  - fs/io_uring.c:io_destruct_skb
  - fs/ext4/super.c:ext4_sync_fs
  - block/bio-integrity.c:blk_flush_integrity
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/md/md.c:md_open
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:new_dev_store
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff810c2d20-ffffffff810c313e: flush_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
