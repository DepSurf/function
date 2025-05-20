# Function: <code>xa_init_flags</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b71dd)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828ab0a7)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81108db5)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828b1368)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff8115af50)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828b6d9b)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8122566c)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff8122b875)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff8125c8a8)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812cd7ac)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fba56)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff81344794)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff8134be91)
Location: include/linux/xarray.h:317
Inline: True
```
```
In ipc/util.c (ffffffff813f0861)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814a323a)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814c1484)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81510df8)
Location: include/linux/xarray.h:317
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816aa9a6)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f828c)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765cd2)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817caf9c)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff8181359a)
Location: include/linux/xarray.h:317
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff818834fb)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff818a7f5d)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff818fd7ba)
Location: include/linux/xarray.h:317
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810ba768)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828c3886)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81112395)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca025)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff81167600)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d03ae)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8123282c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff8123b4e5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff81277a81)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812ea54c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c3b1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8136c9ac)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff81374861)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff8141cd31)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814d12f5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814efc1f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff8153f439)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816e40ad)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731950)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3d8b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180b36b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff81856346)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff818cdb98)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff818f2ef4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8195d19a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810c32b8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828cbe59)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff8111e625)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2583)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff811734c0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d87eb)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81240ad6)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff81249a05)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff81287571)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812fbf7c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f181)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff81384b5c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff8138cae1)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff81436b81)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814ea6a5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff815090cf)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff815602d9)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff8170813d)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755ac0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c77db)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8290c7ca)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183c32b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff818879b1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4193)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff818fff88)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81924e48)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8199362a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810cad4c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff82cede02)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81129d6e)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf2f68)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81184fa2)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff82cf7d97)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81271a96)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff81277c85)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff812b9dbd)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff81334bbf)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813692e8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/io_uring.c (ffffffff8137ce76)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff813cf683)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff813d7fcb)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff81486e31)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In security/apparmor/secid.c (ffffffff81505d05)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_secids_init
```
```
In block/blk-ioc.c (ffffffff81549645)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff8156a259)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81602875)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff817082d3)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/ioasid.c (ffffffff8179326f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/base/swnode.c (ffffffff817c2eac)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff8181399f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818914fb)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff82d213cf)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190f0ce)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff81956991)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c93ab)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d6f38)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819f9438)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81a55f9c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc
```
```
In net/sched/cls_api.c (ffffffff81a6b72a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810656df)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/workqueue.c (ffffffff810c5e7c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff82fda45c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81125772)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdfa3d)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81182112)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff82fe4a90)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff812822a5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff812c582d)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff8134052f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813765c8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/io_uring.c (ffffffff8138a857)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff813e12b3)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff813e9c6b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff814a4451)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In security/apparmor/secid.c (ffffffff81522e55)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_secids_init
```
```
In block/blk-ioc.c (ffffffff81565475)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81584ca9)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81627785)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff816a8f53)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff817254f3)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/ioasid.c (ffffffff817bfcaf)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/base/swnode.c (ffffffff817d7cef)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81822b8f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff81834aee)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f620)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8300f1ba)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81916c2e)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff8195aad1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8fcb)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d6338)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819f9258)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81a5d373)
Location: include/linux/xarray.h:374
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a74136)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065daf)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069854)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff810c77bc)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff831e4df9)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81125a45)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff831ea655)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81183262)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff831ef0b9)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff812873b5)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff812cc502)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff81346a5f)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137ced9)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/io_uring.c (ffffffff81392489)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff813e7ee3)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff813f06c1)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff814aa421)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In security/apparmor/secid.c (ffffffff81529045)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_secids_init
```
```
In block/blk-ioc.c (ffffffff8156dae5)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/genhd.c (ffffffff8157e8ef)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff8158b969)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff8160ada9)
Location: include/linux/xarray.h:376
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8168b703)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81706793)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/ioasid.c (ffffffff817a2ecf)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/base/swnode.c (ffffffff817bb893)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81805b3f)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff81817cbe)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818820b0)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8321a208)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fa0b6)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff8193f87a)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae09b)
Location: include/linux/xarray.h:376
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bc408)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819de8d2)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81a3bc40)
Location: include/linux/xarray.h:376
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a5cc86)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106fecf)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073f34)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff810da51c)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff832c8c79)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff811461ec)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff832ceca8)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff811ab312)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff832d46fb)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff812c6d35)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff813116e1)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff813944bf)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9d89)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/io_uring.c (ffffffff813e04b6)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff81439c23)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff814425b1)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff81502941)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In security/apparmor/secid.c (ffffffff815873e5)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_secids_init
```
```
In block/blk-ioc.c (ffffffff815d20d5)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/genhd.c (ffffffff815e3e30)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff815f0c84)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81679a79)
Location: include/linux/xarray.h:376
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81700806)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81782053)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/ioasid.c (ffffffff8182c20f)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f4e7)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff818457a3)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890c01)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/dax/bus.c (ffffffff818a230e)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81913a50)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff83303d03)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81998de5)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff819e416a)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c69b)
Location: include/linux/xarray.h:376
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff81a6b846)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81a8e6b2)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81af60ee)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/sched/cls_api.c (ffffffff81b15e36)
Location: include/linux/xarray.h:376
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d7e1)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082464)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff810f3c4c)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff8347bdbc)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff8116a455)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/irq/msi.c (ffffffff8116f08c)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In kernel/cgroup/cgroup.c (ffffffff83482a09)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff811dca73)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83488d87)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff81324219)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/list_lru.c (ffffffff81335355)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/swap_state.c (ffffffff8137c815)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff814162df)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8145185a)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff814b4ccd)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff814be331)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff81593ec1)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff8167d71f)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff8168a995)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff816930fd)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff816a211a)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/io_uring.c (ffffffff81e8ec79)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81794f5d)
Location: include/linux/xarray.h:377
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8182e486)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/acpi/scan.c:__acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff818b8a66)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/ioasid.c (ffffffff8196d3fd)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/iommu/virtio-iommu.c (ffffffff819706d7)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81989a63)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da901)
Location: include/linux/xarray.h:377
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819ebb18)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a685fb)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff834bcd35)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af5dbe)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09c45)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81b49338)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc6d7)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81bdc2d7)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81c045f6)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81c76247)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/sched/cls_api.c (ffffffff81c9d441)
Location: include/linux/xarray.h:377
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ed41)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094ed4)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff81115e8c)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff83ea6f62)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff8119efe5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/irq/msi.c (ffffffff811a4f94)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0059)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff812223d3)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83eb9395)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff81398b19)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/list_lru.c (ffffffff813ac00d)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/swap_state.c (ffffffff813f9fe5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff814a1654)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e055a)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8154bbfd)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff81556111)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff8163ca71)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff8173a2ff)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff81749b78)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff81752891)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff817617ec)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/io_uring.c (ffffffff81789fb9)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff8179bb44)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pinctrl/core.c (ffffffff818aa41d)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191c40d)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff8192043f)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/acpi/scan.c (ffffffff819619f5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a05f65)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0e46)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/iommu.c (ffffffff81acdeec)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/iommu/ioasid.c (ffffffff81ad7c3d)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_register_allocator
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb4f7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81af8da3)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b55cd9)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b686e4)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfaf6b)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c836d8)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99a45)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce09a1)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76dd7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81d873d7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81db40c6)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/devlink.c (ffffffff81e2e9d3)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/sched/cls_api.c (ffffffff81e59951)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c31)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097e54)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff81122c2b)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff836cb8c2)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff811b0ec6)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/irq/msi.c (ffffffff811b6f04)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In kernel/cgroup/cgroup.c (ffffffff836d50ab)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81238a04)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff836de9c5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff813cba79)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/list_lru.c (ffffffff813e03ad)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff836e6191)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swap_state.c (ffffffff8142cf25)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff814d6964)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516e0a)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8158388d)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff8158dec1)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff81674f81)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff817769ff)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff8178627c)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff8178ea51)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff817a09d9)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/io_uring.c (ffffffff817ca8c9)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff817dcc74)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pinctrl/core.c (ffffffff818ed4ad)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8195fa0f)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff81963dd5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/acpi/scan.c (ffffffff819a7e05)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a4ee25)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81ac4256)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0d6b6)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/iommu.c (ffffffff81b1ca7c)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b297b7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81b472d2)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba9229)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbbb50)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c605ab)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81cea3fc)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00df5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48b77)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4d17)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81df5847)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81e24776)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff837340d6)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tcf_net_init
```
```
In net/devlink/core.c (ffffffff820420bb)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_alloc_ns
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
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81099010)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f3f3)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In kernel/workqueue.c (ffffffff8112cbf8)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff838fcc92)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff811c0c46)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/irq/msi.c (ffffffff811c6dc4)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_setup_device_data
```
```
In kernel/cgroup/cgroup.c (ffffffff8390740b)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff812526d4)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83911005)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/backing-dev.c (ffffffff813f63e4)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/list_lru.c (ffffffff8140a70d)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
```
```
In mm/vmalloc.c (ffffffff839189f1)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_init
```
```
In mm/swap_state.c (ffffffff81466635)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff81508d54)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/libfs.c (ffffffff81523625)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/libfs.c:simple_offset_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b1fa)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff815bc36c)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff815c6c30)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In ipc/util.c (ffffffff816b1341)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff817b8c2f)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-ioc.c:alloc_io_context
```
```
In block/blk-mq.c (ffffffff817c8958)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/genhd.c (ffffffff817d1340)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff817e4538)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/io_uring.c (ffffffff8180e1d8)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/tctx.c (ffffffff81820f56)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In drivers/pinctrl/core.c (ffffffff81934d52)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff819a9096)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff819ad485)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/acpi/scan.c (ffffffff819f0824)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/dma/dmaengine.c (ffffffff81a9aac5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81b17125)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b62d91)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/intel/nested.c (ffffffff81b6968e)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/intel/nested.c:intel_nested_domain_alloc
```
```
In drivers/iommu/iommu.c (ffffffff81b72f9b)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_alloc
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b807a7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffffffff81b9f661)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd56a)
Location: include/linux/xarray.h:378
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c102c1)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e8a1)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
  - drivers/gpu/drm/drm_auth.c:drm_master_create
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8869f)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_connector_ida_init
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff8395416f)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_core_init
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d9c5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_open
  - drivers/gpu/drm/drm_gem.c:drm_gem_init
```
```
In drivers/gpu/drm/drm_lease.c (ffffffff81c9f9ef)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
```
```
In drivers/gpu/drm/drm_mode_config.c (ffffffff81ca2cab)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init
  - drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init
  - drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb0c75)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_open
```
```
In drivers/accel/drm_accel.c (ffffffff839544d5)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_core_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d16f7b)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9fc88)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6925)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff03a)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ae07)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81eabed7)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bbe)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
```
```
In net/core/net_namespace.c (ffffffff81ee23c6)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eed904)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/core/dev.c:netdev_init
```
```
In net/sched/cls_api.c (ffffffff83968616)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/netlink/genetlink.c (ffffffff81f8fc06)
Location: include/linux/xarray.h:378
Inline: True
```
```
In net/devlink/core.c (ffffffff820feaf0)
Location: include/linux/xarray.h:378
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_alloc_ns
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
In kernel/workqueue.c (ffff800010121038)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffff800011443698)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffff800010183e14)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffff80001144aa74)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffff8000101e7808)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffff800011451344)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffff8000102d25e8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffff8000102df228)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffff8000103220f0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffff8000103aba3c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ebd60)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffff800010453a9c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffff80001045e6b0)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffff80001051d174)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffff8000105e8d80)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffff80001060ba3c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffff80001068ccd8)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbeec)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/swnode.c (ffff8000108f5c68)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffff800010956d10)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe610)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7a0ec)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffff800010ad5484)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b564c4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b802b0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8eec4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffff800010bc093c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffff800010c3fae8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (c0374fa8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (c151d560)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (c03d3028)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (c1524dd8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (c0427be4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c152bcf8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (c04f9ed4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (c050408c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (c053a7a0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (c058c968)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (c05c2e64)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (c06165d4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (c061f114)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (c06d95ac)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (c07954e0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (c07b6af0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (c082ed64)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (c09e2178)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/net/ppp/ppp_generic.c (c0adcb28)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (c0b4da7c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (c0bb474c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37c7c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/remoteproc/remoteproc_core.c (c0c638e8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (c0c78f48)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (c0cdcc24)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (c0d51640)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In arch/powerpc/platforms/powernv/vas.c (c0000000000e1378)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
```
```
In kernel/workqueue.c (c00000000016a59c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (c00000000136775c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (c0000000001de454)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (c00000000137013c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (c0000000002580f4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c000000001378c3c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (c00000000038ff08)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (c00000000039ec50)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (c0000000003f7ab0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (c0000000004a67f8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f377c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (c00000000056cf8c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (c00000000057a6ac)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (c0000000006661d4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (c00000000077d940)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (c0000000007a8b38)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (c0000000008264a0)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (c000000000990c18)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (c000000000a04aec)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6c28)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (c0000000013b0354)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (c000000000b51908)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (c000000000bbb2b4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c7c8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (c000000000c6e790)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (c000000000c9abf0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (c000000000d3a0ac)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffe0000d9f8a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffe000005806)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffe00011afa0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffe00000be6a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffe00015ccc4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffe000010e54)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffe0001ef2ea)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffe0001f6ff0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffe000223136)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffe000270ec6)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffe00029ff9e)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffe0002e6016)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffe0002ee372)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffe000384aec)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffe000429672)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffe000444cb4)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffe000498ed8)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffe000586d7c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c5e38)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062c30c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffe00069183a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffe0006d058e)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/powercap/powercap_sys.c (ffffffe000735356)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffe00074e862)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffe0007af592)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810bd628)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828b4c4c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81116c05)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb434)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff8116bae0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828c169c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81239126)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff81242055)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff8127fb41)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812f455c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327761)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8137d13c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff813850c1)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff8142f161)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814e2c85)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff815016af)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff815588c9)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816cd88d)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a1b0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvme/host/core.c (ffffffff817469df)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c2bb)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f46db)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff8182d831)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818954c3)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In net/core/net_namespace.c (ffffffff818c4e48)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8193349a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810abe58)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828acdcd)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff811078f5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828b3ac7)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff8115ece0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828b9d3c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8122c166)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff81235025)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff812719e1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812e517c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318301)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8136dbfc)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff81375b51)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff8141fbe1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814d3615)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814f1bbf)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81548d89)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816a8bbd)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddc30)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/nvme/host/core.c (ffffffff8172865f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177508b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff828eb652)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b987b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff817f4ec1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/net_namespace.c (ffffffff8187ed88)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff818ecf9a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810bcb88)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828c7b4b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81114af5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce1b7)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff811698b0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d441f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81236ec6)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff8123fdf5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff8127d961)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff812f236c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325231)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8137ac0c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff81382b91)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff8142b301)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814ded15)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff814fd73f)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff81554609)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff816fbdfd)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81748f80)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc65b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff82907bc5)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818311ab)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff8187ce61)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/powercap/powercap_sys.c (ffffffff818f09a8)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81915e48)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8198462a)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/workqueue.c (ffffffff810c4f08)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/pid.c (ffffffff828ccea2)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/irq/irqdomain.c (ffffffff81120125)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup.c (ffffffff828d35b1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff81176fd0)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d9840)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81244576)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In mm/backing-dev.c (ffffffff8124f555)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_bdi_init
```
```
In mm/swap_state.c (ffffffff8128d511)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:init_swap_address_space
```
```
In fs/inode.c (ffffffff8130393c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/inode.c:inode_init_once
  - fs/inode.c:address_space_init_once
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813375d1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8138e70c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In fs/devpts/inode.c (ffffffff813966b1)
Location: include/linux/xarray.h:374
Inline: True
```
```
In ipc/util.c (ffffffff81442251)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In block/blk-ioc.c (ffffffff814f7b85)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-cgroup.c (ffffffff81516cff)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In drivers/pinctrl/core.c (ffffffff8156e499)
Location: include/linux/xarray.h:374
Inline: True
```
```
In drivers/base/swnode.c (ffffffff817168dd)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764400)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_region_create
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d6a0b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8290d82c)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184b37b)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
```
```
In drivers/thermal/thermal_core.c (ffffffff81898891)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905c23)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81911a28)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81937048)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff819a70e1)
Location: include/linux/xarray.h:374
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
```
</details>
</li>
</ul>

## Differences
