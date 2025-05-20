# Function: <code>idr_find_ext</code>

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
In kernel/workqueue.c (ffffffff810a3a8e)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - kernel/workqueue.c:get_work_pool
```
```
In kernel/pid.c (ffffffff810a9e23)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/cgroup/cgroup.c (ffffffff8113508c)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_from_id
```
```
In kernel/bpf/syscall.c (ffffffff811a036f)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811b9e50)
Location: include/linux/idr.h:188
Inline: True
```
```
In mm/memcontrol.c (ffffffff81262523)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be707)
Location: include/linux/idr.h:188
Inline: True
```
```
In fs/kernfs/dir.c (ffffffff812ff299)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In ipc/util.c (ffffffff813a784e)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_rmid
```
```
In ipc/shm.c (ffffffff813aec87)
Location: include/linux/idr.h:188
Inline: True
```
```
In ipc/namespace.c (ffffffff813b3015)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - ipc/namespace.c:free_ipcs
```
```
In block/genhd.c (ffffffff81463bfe)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/bsg.c (ffffffff814713ed)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161fd07)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a324)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
```
```
In drivers/block/loop.c (ffffffff8166fd74)
Location: include/linux/idr.h:188
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff816ca0ee)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/spi/spi.c (ffffffff816f4605)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_unregister_controller
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170619d)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8179078b)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_get_adapter
```
```
In drivers/md/dm.c (ffffffff817c1863)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_md
```
```
In net/core/net_namespace.c (ffffffff8183d1e3)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/sched/act_api.c (ffffffff818817a6)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/genetlink.c (ffffffff8188a9a4)
Location: include/linux/idr.h:188
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
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
