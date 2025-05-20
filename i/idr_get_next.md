# Function: <code>idr_get_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idp, int *nextidp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813e9cd0)
Location: lib/idr.c:736
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:show_workqueue_state
  - kernel/cgroup.c:task_cgroup_path
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
```
**Symbols:**

```
ffffffff813e9cd0-ffffffff813e9dc1: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idp, int *nextidp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff814300b0)
Location: lib/idr.c:736
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/cgroup.c:task_cgroup_path
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
```
**Symbols:**

```
ffffffff814300b0-ffffffff814301a7: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idp, int *nextidp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c2e0)
Location: lib/idr.c:736
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/cgroup.c:task_cgroup_path
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff8144c2e0-ffffffff8144c3d8: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818eca40)
Location: lib/idr.c:123
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff818eca40-ffffffff818ecaa2: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819729d0)
Location: lib/idr.c:110
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff819729d0-ffffffff81972a32: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cef80)
Location: lib/idr.c:230
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_chip_find_get
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff819cef80-ffffffff819cf00a: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a084f0)
Location: lib/idr.c:226
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81a084f0-ffffffff81a08576: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a77e30)
Location: lib/idr.c:227
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81a77e30-ffffffff81a77f30: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf320)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81aaf320-ffffffff81aaf37b: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e9040)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff815e9040-ffffffff815e909a: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e0f0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8160e0f0-ffffffff8160e14a: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1840)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff815f1840-ffffffff815f189a: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165e9b0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_rmid
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff8165e9b0-ffffffff8165ea0a: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778240)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_all_workqueues
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_rmid
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff81778240-ffffffff817782a4: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82020fb0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_all_workqueues
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_rmid
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff82020fb0-ffffffff82021014: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a0fd0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_all_workqueues
  - kernel/pid.c:find_ge_pid
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_rmid
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
```
**Symbols:**

```
ffffffff820a0fd0-ffffffff820a1034: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82178fb0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_all_workqueues
  - kernel/pid.c:find_ge_pid
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_rmid
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_file.c:drm_show_memory_stats
  - drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:_drm_lease_revoke
  - drivers/gpu/drm/drm_lease.c:drm_lease_create
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_getfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_release
```
**Symbols:**

```
ffffffff82178fb0-ffffffff82179014: idr_get_next (STB_GLOBAL)
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
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88b88)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffff800010d88b88-ffff800010d88bfc: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e83a70)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/mtd/mtdcore.c:mtd_proc_show
  - drivers/mtd/mtdcore.c:mtd_proc_show
  - drivers/mtd/mtdcore.c:get_mtd_device_nm
  - drivers/mtd/mtdcore.c:get_mtd_device_nm
  - drivers/mtd/mtdcore.c:get_mtd_device
  - drivers/mtd/mtdcore.c:get_mtd_device
  - drivers/mtd/mtdcore.c:unregister_mtd_user
  - drivers/mtd/mtdcore.c:unregister_mtd_user
  - drivers/mtd/mtdcore.c:register_mtd_user
  - drivers/mtd/mtdcore.c:register_mtd_user
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
c0e83a70-c0e83b1c: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9500)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
c000000000ec9500-c000000000ec9594: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2a50)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffe0008b2a50-ffffffe0008b2a98: idr_get_next (STB_GLOBAL)
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
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e170)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81a4e170-ffffffff81a4e1cb: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b260)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81a0b260-ffffffff81a0b2bb: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aba560)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81aba560-ffffffff81aba5bb: idr_get_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *idr_get_next(struct idr *idr, int *nextid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac69b0)
Location: lib/idr.c:264
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:show_workqueue_state
  - kernel/pid.c:find_ge_pid
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - drivers/char/tpm/tpm-chip.c:tpm_default_chip
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/pps/pps.c:pps_lookup_dev
  - net/netlink/genetlink.c:genl_unbind
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:ctrl_dumpfamily
  - net/netlink/genetlink.c:genl_family_find_byname
```
**Symbols:**

```
ffffffff81ac69b0-ffffffff81ac6a0b: idr_get_next (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct idr *idr</code>
</li>
<li>
<b>Param added. </b>
<code>int *nextid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr *idp</code>
</li>
<li>
<b>Param removed. </b>
<code>int *nextidp</code>
</li>
</ul>
</details>
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
