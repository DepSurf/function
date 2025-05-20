# Function: <code>__flush_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2797
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
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/io-pgfault.c:iopf_queue_flush_dev
  - drivers/scsi/hosts.c:scsi_flush_work
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_open
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:flush_rdev_wq
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:local_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff81e54a96-ffffffff81e54aab: __flush_workqueue.cold (STB_LOCAL)
ffffffff810f1f80-ffffffff810f2351: __flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2797
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
  - drivers/pci/doe.c:pci_doe_flush_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/io-pgfault.c:iopf_queue_flush_dev
  - drivers/scsi/hosts.c:scsi_flush_work
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/md.c:flush_rdev_wq
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff820565b8-ffffffff820565cd: __flush_workqueue.cold (STB_LOCAL)
ffffffff81112db0-ffffffff81113181: __flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3113
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
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_remove_query_handler
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/iommu/io-pgfault.c:iopf_queue_flush_dev
  - drivers/scsi/hosts.c:scsi_flush_work
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop_writes
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:action_store
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff820d4adf-ffffffff820d4af4: __flush_workqueue.cold (STB_LOCAL)
ffffffff8111f140-ffffffff8111f51e: __flush_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __flush_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3134
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
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/ec.c:acpi_ec_remove_query_handler
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/ec.c:__acpi_ec_flush_work
  - drivers/acpi/thermal.c:acpi_thermal_suspend
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/iommu/io-pgfault.c:iopf_queue_flush_dev
  - drivers/scsi/hosts.c:scsi_flush_work
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_internal_suspend_fast
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush
  - drivers/edac/wq.c:edac_stop_work
  - net/sched/cls_api.c:unregister_tcf_proto_ops
```
**Symbols:**

```
ffffffff821afa2b-ffffffff821afa40: __flush_workqueue.cold (STB_LOCAL)
ffffffff811293f0-ffffffff811297ce: __flush_workqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
