# Function: <code>idr_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void idr_remove(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813e9fc0)
Location: lib/idr.c:550
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/cgroup.c:cgroup_idr_remove
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - ipc/util.c:ipc_rmid
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - lib/idr.c:ida_remove
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/dm.c:free_minor
  - drivers/mmc/core/host.c:mmc_host_classdev_release
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff813e9fc0-ffffffff813ea215: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void idr_remove(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430390)
Location: lib/idr.c:550
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - ipc/util.c:ipc_rmid
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - lib/idr.c:ida_remove
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/dm.c:free_minor
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff81430390-ffffffff814305c4: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void idr_remove(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c560)
Location: lib/idr.c:550
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - ipc/util.c:ipc_rmid
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - lib/idr.c:ida_remove
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:chan_dev_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device
  - drivers/md/dm.c:free_minor
  - net/core/net_namespace.c:cleanup_net
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8144c560-ffffffff8144c796: idr_remove (STB_GLOBAL)
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
In kernel/workqueue.c (ffffffff810a00a3)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/cgroup/cgroup.c (ffffffff81121cc6)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
```
```
In kernel/bpf/syscall.c (ffffffff81191969)
Location: include/linux/idr.h:91
Inline: True
```
```
In kernel/events/core.c (ffffffff811a1f1c)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/shmem.c (ffffffff811db372)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/memcontrol.c (ffffffff81900661)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b3c7)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In ipc/util.c (ffffffff81383155)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
```
```
In block/genhd.c (ffffffff81438538)
Location: include/linux/idr.h:91
Inline: True
```
```
In block/bsg.c (ffffffff814440db)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815b8a29)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3e08)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/block/loop.c (ffffffff81607c33)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
```
```
In drivers/scsi/sg.c (ffffffff81660101)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81698fb8)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hcd.c (ffffffff816af5db)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_deregister_bus
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81721450)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/md/dm.c (ffffffff8174d6b8)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - drivers/md/dm.c:free_minor
```
```
In drivers/powercap/powercap_sys.c (ffffffff817a28f7)
Location: include/linux/idr.h:91
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c38f8)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/netlink/genetlink.c (ffffffff8180c573)
Location: include/linux/idr.h:91
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
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
In kernel/workqueue.c (ffffffff810a6dc1)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/pid.c (ffffffff810aa0a4)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff81133d1b)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
```
```
In kernel/bpf/syscall.c (ffffffff8119e8af)
Location: include/linux/idr.h:148
Inline: True
```
```
In kernel/events/core.c (ffffffff811b5b82)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
```
```
In mm/shmem.c (ffffffff811f1172)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
```
```
In mm/memcontrol.c (ffffffff8198a657)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be7d7)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
```
In fs/kernfs/dir.c (ffffffff812fe4d8)
Location: include/linux/idr.h:148
Inline: True
```
```
In ipc/util.c (ffffffff813a7426)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff81463f98)
Location: include/linux/idr.h:148
Inline: True
```
```
In block/bsg.c (ffffffff81470e7e)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161f579)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
```
```
In drivers/iommu/intel-svm.c (ffffffff8163ab52)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
```
In drivers/block/loop.c (ffffffff81670303)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
```
```
In drivers/scsi/sg.c (ffffffff816c9711)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/spi/spi.c (ffffffff816f46db)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705da8)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hcd.c (ffffffff8171ac0b)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_deregister_bus
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817927d6)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/md/dm.c (ffffffff817bf8a8)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - drivers/md/dm.c:free_minor
```
```
In drivers/powercap/powercap_sys.c (ffffffff81819a37)
Location: include/linux/idr.h:148
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183d3b8)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/netlink/genetlink.c (ffffffff8188b553)
Location: include/linux/idr.h:148
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_unregister_family
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cef40)
Location: lib/idr.c:155
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_free_secid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:__tcf_idr_release
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819cef40-ffffffff819cef53: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a083e0)
Location: lib/idr.c:151
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:free_dev
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a083e0-ffffffff81a083f3: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77d20)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a77d20-ffffffff81a77d33: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf110)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81aaf110-ffffffff81aaf123: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8e40)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_free_secid
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:unhash_nsid
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff815e8e40-ffffffff815e8e53: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160def0)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:__io_destroy_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_remove_buffers
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_free_secid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:unhash_nsid
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8160def0-ffffffff8160df03: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1640)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_free_secid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_action_delete
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff815f1640-ffffffff815f1653: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e7b0)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_free_id
  - kernel/bpf/syscall.c:bpf_prog_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_free_secid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:tcf_del_walker
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8165e7b0-ffffffff8165e7c3: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81777fe0)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_free_id
  - kernel/bpf/syscall.c:bpf_prog_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81777fe0-ffffffff81777ffd: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020d10)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff82020d10-ffffffff82020d2d: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0d30)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/vmscan.c:free_prealloced_shrinker
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff820a0d30-ffffffff820a0d4d: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178d10)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shrinker.c:shrinker_free
  - mm/shrinker.c:shrinker_alloc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/gpu/drm/drm_auth.c:drm_master_release
  - drivers/gpu/drm/drm_connector.c:drm_connector_cleanup
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_delete
  - drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked
  - drivers/gpu/drm/drm_lease.c:_drm_lease_revoke
  - drivers/gpu/drm/drm_lease.c:drm_lease_destroy
  - drivers/gpu/drm/drm_mode_object.c:drm_mode_object_unregister
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_destroy_ioctl
  - drivers/accel/drm_accel.c:accel_minor_remove
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/interconnect/core.c:icc_node_destroy
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff82178d10-ffffffff82178d2d: idr_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88958)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_minor
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel
  - drivers/of/overlay.c:free_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffff800010d88958-ffff800010d88978: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83814)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/mtd/mtdcore.c:del_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_minor
  - drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel
  - drivers/of/overlay.c:free_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c0e83814-c0e83834: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9180)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_minor
  - drivers/of/overlay.c:free_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c000000000ec9180-c000000000ec91b8: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b28c8)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_minor
  - drivers/of/overlay.c:free_overlay_changeset
  - drivers/of/overlay.c:init_overlay_changeset
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/sched/act_api.c:__tcf_action_put
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffe0008b28c8-ffffffe0008b28e8: idr_remove (STB_GLOBAL)
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
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4df60)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a4df60-ffffffff81a4df73: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b050)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a0b050-ffffffff81a0b063: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba350)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81aba350-ffffffff81aba363: idr_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *idr_remove(struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac67a0)
Location: lib/idr.c:152
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:free_pid
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/bpf/syscall.c:bpf_map_free_id
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - mm/shmem.c:shmem_evict_inode
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - block/bsg.c:bsg_register_queue
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/char/tpm/tpm-chip.c:tpm_dev_release
  - drivers/iommu/intel-pasid.c:intel_pasid_free_id
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/usb/core/hcd.c:usb_deregister_bus
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/md/dm.c:free_dev
  - drivers/md/dm.c:alloc_dev
  - drivers/remoteproc/remoteproc_core.c:rproc_free_vring
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_cleanup
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81ac67a0-ffffffff81ac67b3: idr_remove (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
