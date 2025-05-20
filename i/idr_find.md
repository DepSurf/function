# Function: <code>idr_find</code>

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
In kernel/workqueue.c (ffffffff81097a9e)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/cgroup.c (ffffffff811199ed)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/cgroup.c:css_from_id
```
```
In kernel/events/core.c (ffffffff8117ec59)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81252094)
Location: include/linux/idr.h:115
Inline: True
```
```
In ipc/util.c (ffffffff813247e7)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_get_maxid
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipcget
```
```
In ipc/shm.c (ffffffff8132aaa4)
Location: include/linux/idr.h:115
Inline: True
```
```
In ipc/namespace.c (ffffffff8132ead9)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff813cab64)
Location: include/linux/idr.h:115
Inline: True
```
```
In block/bsg.c (ffffffff813d659d)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/iommu/intel-svm.c (ffffffff8153b852)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/block/loop.c (ffffffff8156f741)
Location: include/linux/idr.h:115
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff815c33bf)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f847d)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core.c (ffffffff8167b034)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff816a412e)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff81710b78)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
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
In kernel/workqueue.c (ffffffff8109b17a)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/cgroup.c (ffffffff811216d5)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/cgroup.c:css_from_id
```
```
In kernel/events/core.c (ffffffff81190735)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memcontrol.c (ffffffff8122464c)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a854)
Location: include/linux/idr.h:115
Inline: True
```
```
In ipc/util.c (ffffffff813593d7)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_get_maxid
```
```
In ipc/shm.c (ffffffff8135f754)
Location: include/linux/idr.h:115
Inline: True
```
```
In ipc/namespace.c (ffffffff81363799)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff8140ee34)
Location: include/linux/idr.h:115
Inline: True
```
```
In block/bsg.c (ffffffff8141bfcd)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/iommu/intel-svm.c (ffffffff815906d9)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/block/loop.c (ffffffff815c5061)
Location: include/linux/idr.h:115
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8161bbdf)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816560d1)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core.c (ffffffff816dcab8)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff817042c9)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff817784a8)
Location: include/linux/idr.h:115
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
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
In kernel/workqueue.c (ffffffff8109ff5a)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/cgroup.c (ffffffff81129c55)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - kernel/cgroup.c:css_from_id
```
```
In kernel/events/core.c (ffffffff8119f602)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memcontrol.c (ffffffff81236c1c)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e404)
Location: include/linux/idr.h:140
Inline: True
```
```
In ipc/util.c (ffffffff8136f8c7)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_get_maxid
```
```
In ipc/shm.c (ffffffff81375f54)
Location: include/linux/idr.h:140
Inline: True
```
```
In ipc/namespace.c (ffffffff81379fa9)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff8142a1d4)
Location: include/linux/idr.h:140
Inline: True
```
```
In block/bsg.c (ffffffff8143710d)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815a50ec)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
```
```
In drivers/iommu/intel-svm.c (ffffffff815bdf69)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/block/loop.c (ffffffff815f3791)
Location: include/linux/idr.h:140
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8164c82f)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81683dab)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ce38)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff81736199)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff817a54d3)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/netlink/genetlink.c (ffffffff817eba94)
Location: include/linux/idr.h:140
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
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
In kernel/workqueue.c (ffffffff8109d34b)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/cgroup/cgroup.c (ffffffff81128a39)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_from_id
```
```
In kernel/bpf/syscall.c (ffffffff8119267a)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811a6253)
Location: include/linux/idr.h:131
Inline: True
```
```
In mm/memcontrol.c (ffffffff812426e3)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b2f0)
Location: include/linux/idr.h:131
Inline: True
```
```
In ipc/util.c (ffffffff81383539)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_get_maxid
```
```
In ipc/shm.c (ffffffff81389ac0)
Location: include/linux/idr.h:131
Inline: True
```
```
In ipc/namespace.c (ffffffff8138dba2)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff81438497)
Location: include/linux/idr.h:131
Inline: True
```
```
In block/bsg.c (ffffffff814444cd)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815b91c7)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3629)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/block/loop.c (ffffffff81607851)
Location: include/linux/idr.h:131
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81660f8b)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816993a5)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f828)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff8174f640)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff817c3743)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/netlink/genetlink.c (ffffffff8180ba10)
Location: include/linux/idr.h:131
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
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
In kernel/workqueue.c (ffffffff810a3a8b)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/pid.c (ffffffff810a9e20)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/cgroup/cgroup.c (ffffffff81135089)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_from_id
```
```
In kernel/bpf/syscall.c (ffffffff811a036c)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811b9e49)
Location: include/linux/idr.h:193
Inline: True
```
```
In mm/memcontrol.c (ffffffff81262523)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be707)
Location: include/linux/idr.h:193
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812ff299)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In ipc/util.c (ffffffff813a784e)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_rmid
```
```
In ipc/shm.c (ffffffff813aec87)
Location: include/linux/idr.h:193
Inline: True
```
```
In ipc/namespace.c (ffffffff813b3012)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff81463bfc)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/bsg.c (ffffffff814713ed)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161fd07)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a324)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/block/loop.c (ffffffff8166fd71)
Location: include/linux/idr.h:193
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff816ca0eb)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/spi/spi.c (ffffffff816f4605)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170619a)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81790788)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff817c1860)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff8183d1e3)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/netlink/genetlink.c (ffffffff8188a9a0)
Location: include/linux/idr.h:193
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cef60)
Location: lib/idr.c:175
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/act_api.c:tcf_idr_check
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff819cef60-ffffffff819cef71: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a08400)
Location: lib/idr.c:171
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a08400-ffffffff81a08411: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77d40)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a77d40-ffffffff81a77d51: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf130)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81aaf130-ffffffff81aaf141: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e8e60)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_charge
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff815e8e60-ffffffff815e8e71: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160df10)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_charge
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_remove_buffers
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_delete_index
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8160df10-ffffffff8160df21: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1660)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_action_delete
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff815f1660-ffffffff815f1671: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e7d0)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_obtain_object_check
  - ipc/namespace.c:free_ipcs
  - security/apparmor/secid.c:apparmor_secid_to_secctx
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8165e7d0-ffffffff8165e7e1: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778000)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_obtain_object_check
  - ipc/shm.c:shmctl_shm_info
  - ipc/namespace.c:free_ipcs
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_install
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81778000-ffffffff81778019: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020d40)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:ipc_obtain_object_check
  - ipc/shm.c:shmctl_shm_info
  - ipc/namespace.c:free_ipcs
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_install
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - drivers/interconnect/core.c:icc_get
  - drivers/interconnect/core.c:icc_get
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff82020d40-ffffffff82020d59: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0d60)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/vmscan.c:shrink_slab_memcg
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:ipc_obtain_object_check
  - ipc/shm.c:shmctl_shm_info
  - ipc/namespace.c:free_ipcs
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_install
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff820a0d60-ffffffff820a0d79: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178d40)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:try_to_grab_pending
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_init_event
  - mm/shrinker.c:shrink_slab_memcg
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - ipc/util.c:ipc_obtain_object_check
  - ipc/shm.c:shmctl_shm_info
  - ipc/namespace.c:free_ipcs
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/gpu/drm/drm_auth.c:drm_authmagic
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:objects_lookup
  - drivers/gpu/drm/drm_lease.c:drm_mode_revoke_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_lease_create
  - drivers/gpu/drm/drm_lease.c:drm_lease_create
  - drivers/gpu/drm/drm_lease.c:drm_lease_filter_crtcs
  - drivers/gpu/drm/drm_lease.c:drm_lease_held
  - drivers/gpu/drm/drm_lease.c:_drm_lease_held
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find
  - drivers/accel/drm_accel.c:accel_minor_acquire
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_install
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_link_create
  - drivers/interconnect/core.c:icc_node_destroy
  - drivers/interconnect/core.c:icc_node_create
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff82178d40-ffffffff82178d59: idr_find (STB_GLOBAL)
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
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88978)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/firmware/arm_scmi/bus.c:scmi_dev_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffff800010d88978-ffff800010d88994: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83834)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/shm.c:ksys_shmctl
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/mtd/mtdcore.c:get_mtd_device
  - drivers/mtd/mtdcore.c:del_mtd_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/firmware/arm_scmi/bus.c:scmi_dev_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c0e83834-c0e83850: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec91c0)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/of/overlay.c:of_overlay_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
c000000000ec91c0-c000000000ec91f4: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b28e8)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/of/overlay.c:of_overlay_remove
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffe0008b28e8-ffffffe0008b2906: idr_find (STB_GLOBAL)
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
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4df80)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a4df80-ffffffff81a4df91: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b070)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81a0b070-ffffffff81a0b081: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba370)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81aba370-ffffffff81aba381: idr_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *idr_find(const struct idr *idr, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac67c0)
Location: lib/idr.c:172
Inline: False
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
  - kernel/cgroup/cgroup.c:css_from_id
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_rmid
  - ipc/namespace.c:free_ipcs
  - block/genhd.c:get_gendisk
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-pasid.c:intel_pasid_lookup_id
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/sched/cls_api.c:tcf_block_refcnt_get
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff81ac67c0-ffffffff81ac67d1: idr_find (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
