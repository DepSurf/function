# Function: <code>idr_find_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *idr_find_slowpath(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea650)
Location: lib/idr.c:642
Inline: True
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/cgroup.c:css_from_id
  - kernel/events/core.c:perf_event_alloc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipc_get_maxid
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipcget
  - ipc/namespace.c:free_ipcs
  - block/bsg.c:bsg_open
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
```
**Symbols:**

```
ffffffff813ea650-ffffffff813ea6bf: idr_find_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *idr_find_slowpath(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430a10)
Location: lib/idr.c:642
Inline: True
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/cgroup.c:css_from_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_get_maxid
  - ipc/namespace.c:free_ipcs
  - block/bsg.c:bsg_open
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
```
**Symbols:**

```
ffffffff81430a10-ffffffff81430a7f: idr_find_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *idr_find_slowpath(struct idr *idp, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144cbe0)
Location: lib/idr.c:642
Inline: True
Direct callers:
  - kernel/workqueue.c:get_work_pool
  - kernel/cgroup.c:css_from_id
  - kernel/events/core.c:perf_event_alloc
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:sysvipc_find_ipc
  - ipc/util.c:ipcget
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_get_maxid
  - ipc/namespace.c:free_ipcs
  - block/bsg.c:bsg_open
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_devstrs
  - drivers/scsi/sg.c:sg_proc_seq_show_dev
  - drivers/scsi/sg.c:sg_open
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/i2c/i2c-core.c:i2c_get_adapter
  - drivers/md/dm.c:dm_get_md
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_unregister_family
```
**Symbols:**

```
ffffffff8144cbe0-ffffffff8144cc4d: idr_find_slowpath (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
