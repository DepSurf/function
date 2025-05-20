# Function: <code>idr_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void idr_destroy(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea240)
Location: lib/idr.c:631
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_free_root
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_init
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - lib/idr.c:ida_destroy
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff813ea240-ffffffff813ea39b: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void idr_destroy(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff814305f0)
Location: lib/idr.c:631
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_mount
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - lib/idr.c:ida_destroy
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff814305f0-ffffffff8143074b: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void idr_destroy(struct idr *idp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c7c0)
Location: lib/idr.c:631
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_mount
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - lib/idr.c:ida_destroy
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff8144c7c0-ffffffff8144c91c: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0f80)
Location: lib/radix-tree.c:2223
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff818f0f80-ffffffff818f0fb0: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819773d0)
Location: lib/radix-tree.c:2220
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff819773d0-ffffffff81977400: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3b60)
Location: lib/radix-tree.c:2221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff819d3b60-ffffffff819d3b91: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cde0)
Location: lib/radix-tree.c:1581
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a0cde0-ffffffff81a0ceb3: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c750)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a7c750-ffffffff81a7c805: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3a80)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81ab3a80-ffffffff81ab3b35: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815edbc0)
Location: lib/radix-tree.c:1560
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:unhash_nsid
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff815edbc0-ffffffff815edbf4: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816122f0)
Location: lib/radix-tree.c:1560
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:unhash_nsid
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff816122f0-ffffffff81612324: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5950)
Location: lib/radix-tree.c:1561
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff815f5950-ffffffff815f5a04: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662db0)
Location: lib/radix-tree.c:1561
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81662db0-ffffffff81662e7b: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177cf20)
Location: lib/radix-tree.c:1561
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff8177cf20-ffffffff8177cff7: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820397d0)
Location: lib/radix-tree.c:1561
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff820397d0-ffffffff820398a7: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7af0)
Location: lib/radix-tree.c:1559
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff820b7af0-ffffffff820b7bc7: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82192400)
Location: lib/radix-tree.c:1559
Inline: False
Direct callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/gpu/drm/drm_auth.c:drm_master_destroy
  - drivers/gpu/drm/drm_auth.c:drm_master_destroy
  - drivers/gpu/drm/drm_auth.c:drm_master_destroy
  - drivers/gpu/drm/drm_drv.c:drm_core_init
  - drivers/gpu/drm/drm_gem.c:drm_gem_release
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_release
  - drivers/accel/drm_accel.c:accel_core_exit
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff82192400-ffffffff821924d7: idr_destroy (STB_GLOBAL)
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
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8d738)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffff800010d8d738-ffff800010d8d83c: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e87d14)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/mtd/mtdcore.c:cleanup_mtd
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/firmware/arm_scmi/driver.c:scmi_remove
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
c0e87d14-c0e87e34: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecfd50)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
c000000000ecfd50-c000000000ecfec0: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6998)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffe0008b6998-ffffffe0008b6a5e: idr_destroy (STB_GLOBAL)
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
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a528d0)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a528d0-ffffffff81a52985: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f9d0)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81a0f9d0-ffffffff81a0fa85: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abecc0)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81abecc0-ffffffff81abed75: idr_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void idr_destroy(struct idr *idr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb180)
Location: lib/radix-tree.c:1568
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:destroy_pid_namespace
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv
  - fs/kernfs/dir.c:kernfs_create_root
  - ipc/msg.c:msg_exit_ns
  - ipc/sem.c:sem_exit_ns
  - ipc/shm.c:shm_exit_ns
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/block/loop.c:loop_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/usb.c:usb_exit
  - drivers/md/dm.c:dm_exit
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/powercap/powercap_sys.c:powercap_release
  - net/core/net_namespace.c:cleanup_net
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/act_api.c:tcf_idrinfo_destroy
```
**Symbols:**

```
ffffffff81acb180-ffffffff81acb235: idr_destroy (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct idr *idp</code>
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
