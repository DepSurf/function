# Function: <code>idr_remove_ext</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6dc1)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/pid.c (ffffffff810aa0a4)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff81133d20)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
```
```
In kernel/bpf/syscall.c (ffffffff8119e8b3)
Location: include/linux/idr.h:143
Inline: True
```
```
In kernel/events/core.c (ffffffff811b5b82)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/shmem.c (ffffffff811f1176)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/memcontrol.c (ffffffff8198a657)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be7d7)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/kernfs/dir.c (ffffffff812fe4dc)
Location: include/linux/idr.h:143
Inline: True
```
```
In ipc/util.c (ffffffff813a7426)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff81463f9a)
Location: include/linux/idr.h:143
Inline: True
```
```
In block/bsg.c (ffffffff81470e85)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f580)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
```
```
In drivers/iommu/intel-svm.c (ffffffff8163ab52)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/block/loop.c (ffffffff81670307)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
```
```
In drivers/scsi/sg.c (ffffffff816c9715)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/spi/spi.c (ffffffff816f46db)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705daf)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hcd.c (ffffffff8171ac0f)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_deregister_bus
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817927dd)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/md/dm.c (ffffffff817bf8ab)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - drivers/md/dm.c:free_minor
```
```
In drivers/powercap/powercap_sys.c (ffffffff81819a47)
Location: include/linux/idr.h:143
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183d3b8)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/sched/act_api.c (ffffffff81881e48)
Location: include/linux/idr.h:143
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff8188b557)
Location: include/linux/idr.h:143
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
</details>
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
