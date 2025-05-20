# Function: <code>idr_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void idr_init(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea3a0)
Location: lib/idr.c:838
Inline: True
Inline callers:
  - lib/idr.c:ida_init
Direct callers:
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_fill_super
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - ipc/util.c:ipc_init_ids
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff813ea3a0-ffffffff813ea3cd: idr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void idr_init(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff814307a8)
Location: lib/idr.c:838
Inline: True
Inline callers:
  - lib/idr.c:ida_init
Direct callers:
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/events/core.c:perf_event_init
  - mm/shmem.c:shmem_fill_super
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - ipc/util.c:ipc_init_ids
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81430750-ffffffff8143077d: idr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void idr_init(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c978)
Location: lib/idr.c:838
Inline: True
Inline callers:
  - lib/idr.c:ida_init
Direct callers:
  - kernel/cgroup.c:cgroup_init_subsys
  - kernel/events/core.c:perf_event_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - ipc/util.c:ipc_init_ids
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff8144c920-ffffffff8144c94d: idr_init (STB_GLOBAL)
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
In kernel/cgroup/cgroup.c (ffffffff820c7709)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/events/core.c (ffffffff820cd09b)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff811d8081)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b25a)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In ipc/util.c (ffffffff81382f87)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/iommu/intel-svm.c (ffffffff815d44e7)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169811d)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffff817a2b9f)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff817c32e1)
Location: include/linux/idr.h:96
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
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
In kernel/pid.c (ffffffff826ca093)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff826cfd6a)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff8113f913)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff826d5ad9)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff811ed5e1)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be66a)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/kernfs/dir.c (ffffffff812ff750)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff813a70a4)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b277)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81702fed)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffff81819cdf)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff8183ce31)
Location: include/linux/idr.h:153
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
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
In kernel/pid.c (ffffffff826f42bf)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa493)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff8114e270)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff826ffd31)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8121029c)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e6e6b)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8132d3f4)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff813d61c5)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/iommu/intel-svm.c (ffffffff81676ad0)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81741bc2)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffff81863d6b)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff818876bd)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff818d2221)
Location: include/linux/idr.h:138
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/pid.c (ffffffff828ab0a7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828b1368)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff8115af50)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828b6d9b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8122566c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fba56)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff81344794)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff813f0861)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765cd2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffff818834fb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff818a7f5d)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff818fd7ba)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828c3886)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca025)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff81167600)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d03ae)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8123282c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c3b1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8136c9ac)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff8141cd31)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3d8b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffff818cdb98)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff818f2ef4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8195d19a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828cbe59)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2583)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff811734c0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d87eb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81240ad6)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f181)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff81384b5c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81436b81)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c77db)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8290c7ca)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4193)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff818fff88)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81924e48)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8199362a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff82cede02)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf2f68)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81184fa2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff82cf7d97)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81271a96)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813692e8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/io_uring.c (ffffffff8137ce76)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff813cf683)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81486e31)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818914fb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff82d213cf)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c93ab)
Location: include/linux/idr.h:149
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d6f38)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819f9438)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81a6b72a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff82fda45c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdfa3d)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81182112)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff82fe4a90)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813765c8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/io_uring.c (ffffffff8138b66e)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/kernfs/dir.c (ffffffff813e12b3)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff814a4451)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f620)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8300f1ba)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8fcb)
Location: include/linux/idr.h:149
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d6338)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819f9258)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81a74136)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff831e4df9)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff831ea655)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81183262)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff831ef0b9)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137ced9)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff813e7ee3)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff814aa421)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818820b0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8321a208)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae09b)
Location: include/linux/idr.h:149
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bc408)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff819de8d2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81a5cc86)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff832c8c79)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff832ceca8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff811ab312)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff832d46fb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9d89)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff81439c23)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81502941)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81913a50)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff83303d03)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c69b)
Location: include/linux/idr.h:149
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff81a6b846)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81a8e6b2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81b15e36)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff8347bdbc)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff83482a09)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff811dca73)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83488d87)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8145185a)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff814b4ccd)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81593ec1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a685fb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09c45)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc6d7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81bdc2d7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81c045f6)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81c9d441)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff83ea6f62)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0059)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff812223d3)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83eb9395)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e055a)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8154bbfd)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff8163ca71)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfaf6b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99a45)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76dd7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81d873d7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81db40c6)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81e59951)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff836cb8c2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff836d50ab)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff81238a04)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff836de9c5)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516e0a)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8158388d)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81674f81)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c605ab)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00df5)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4d17)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81df5847)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81e24776)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81eb5391)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/pid.c (ffffffff838fcc92)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff8390740b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
```
```
In kernel/pid_namespace.c (ffffffff812526d4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/events/core.c (ffffffff83911005)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b1fa)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff815bc36c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff816b1341)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e8d7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff8395416f)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_core_init
```
```
In drivers/gpu/drm/drm_lease.c (ffffffff81c9f9ef)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
```
```
In drivers/accel/drm_accel.c (ffffffff839544d5)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_core_init
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d16f7b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6925)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ae07)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81eabed7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In net/core/net_namespace.c (ffffffff81ee23c6)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff81f780a1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
In kernel/pid.c (ffff800011443698)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffff80001144aa74)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffff8000101e7808)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffff800011451344)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffff8000102d25e8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ebd60)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffff800010453a9c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffff80001051d174)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe610)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b564c4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b802b0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8eec4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffff800010bc093c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffff800010c3fae8)
Location: include/linux/idr.h:149
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
In kernel/pid.c (c151d560)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (c1524dd8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (c0427be4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c152bcf8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (c04f9ed4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (c05c2e64)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (c06165d4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (c06d95ac)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (c0adcb28)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37c7c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/remoteproc/remoteproc_core.c (c0c638e8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (c0c78f48)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (c0cdcc24)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (c0d51640)
Location: include/linux/idr.h:149
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
In kernel/pid.c (c00000000136775c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (c00000000137013c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (c0000000002580f4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c000000001378c3c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (c00000000038ff08)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f377c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (c00000000056cf8c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (c0000000006661d4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6c28)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (c0000000013b0354)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c7c8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (c000000000c6e790)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (c000000000c9abf0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (c000000000d3a0ac)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffe000005806)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffe00000be6a)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffe00015ccc4)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffe000010e54)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffe0001ef2ea)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffe00029ff9e)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffe0002e6016)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffe000384aec)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062c30c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/powercap/powercap_sys.c (ffffffe000735356)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffe00074e862)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffe0007af592)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828b4c4c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb434)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff8116bae0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828c169c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81239126)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327761)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8137d13c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff8142f161)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c2bb)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818954c3)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In net/core/net_namespace.c (ffffffff818c4e48)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8193349a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828acdcd)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828b3ac7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff8115ece0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828b9d3c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff8122c166)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318301)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8136dbfc)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff8141fbe1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8177508b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff828eb652)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In net/core/net_namespace.c (ffffffff8187ed88)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff818ecf9a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828c7b4b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce1b7)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff811698b0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d441f)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81236ec6)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325231)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8137ac0c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff8142b301)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc65b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff82907bc5)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/powercap/powercap_sys.c (ffffffff818f09a8)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81915e48)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff8198462a)
Location: include/linux/idr.h:149
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
In kernel/pid.c (ffffffff828ccea2)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
```
```
In kernel/cgroup/cgroup.c (ffffffff828d35b1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:init_cgroup_root
```
```
In kernel/pid_namespace.c (ffffffff81176fd0)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff828d9840)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/shmem.c (ffffffff81244576)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fill_super
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813375d1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/kernfs/dir.c (ffffffff8138e70c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
```
```
In ipc/util.c (ffffffff81442251)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_ids
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d6a0b)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In drivers/vfio/vfio.c (ffffffff8290d82c)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905c23)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
```
```
In drivers/powercap/powercap_sys.c (ffffffff81911a28)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
```
In net/core/net_namespace.c (ffffffff81937048)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/sched/cls_api.c (ffffffff819a70e1)
Location: include/linux/idr.h:149
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_init
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
</ul>
