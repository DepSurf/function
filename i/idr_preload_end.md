# Function: <code>idr_preload_end</code>

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
In kernel/cgroup.c (ffffffff81113907)
Location: include/linux/idr.h:98
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812526ea)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In ipc/util.c (ffffffff81324afb)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff813caf6e)
Location: include/linux/idr.h:98
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff815c45d0)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff816a3378)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
```
In drivers/mmc/core/host.c (ffffffff816c1f74)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
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
In kernel/cgroup.c (ffffffff8111ad17)
Location: include/linux/idr.h:98
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127aea7)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In ipc/util.c (ffffffff813596fc)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff8140f237)
Location: include/linux/idr.h:98
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8161cde0)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff81703c05)
Location: include/linux/idr.h:98
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
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
In kernel/cgroup.c (ffffffff81122a47)
Location: include/linux/idr.h:123
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128ea57)
Location: include/linux/idr.h:123
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In ipc/util.c (ffffffff8136fbdc)
Location: include/linux/idr.h:123
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff8142a5d7)
Location: include/linux/idr.h:123
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8164d9f0)
Location: include/linux/idr.h:123
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff81735aca)
Location: include/linux/idr.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
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
In kernel/cgroup/cgroup.c (ffffffff81122817)
Location: include/linux/idr.h:114
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b871)
Location: include/linux/idr.h:114
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In ipc/util.c (ffffffff813830ce)
Location: include/linux/idr.h:114
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff81438887)
Location: include/linux/idr.h:114
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff816622e8)
Location: include/linux/idr.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff8174eefd)
Location: include/linux/idr.h:114
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
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
In kernel/pid.c (ffffffff810aa076)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8112e4f7)
Location: include/linux/idr.h:171
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812bec81)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/kernfs/dir.c (ffffffff812fe32c)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff813a71a3)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff8146481a)
Location: include/linux/idr.h:171
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff816cb55d)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff817c114b)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
```
In net/sched/act_api.c (ffffffff818821b4)
Location: include/linux/idr.h:171
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
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
In kernel/pid.c (ffffffff810b0c98)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8113c977)
Location: include/linux/idr.h:161
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811b5f51)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811c8b53)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e74f5)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8132c340)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff813d62b3)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/secid.c (ffffffff81444664)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In block/genhd.c (ffffffff81498130)
Location: include/linux/idr.h:161
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81707f45)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff818097b4)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
```
In net/sched/act_api.c (ffffffff818d594d)
Location: include/linux/idr.h:161
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
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
In kernel/pid.c (ffffffff810b9d93)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff81148037)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811c540d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/btf.c (ffffffff811dc853)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fc4d1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff81343d30)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff813f0956)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814b2250)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693ee6)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff81729055)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff818358be)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
```
In net/sched/cls_api.c (ffffffff818ff6c2)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810bfc8a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff81153399)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d5320)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f1fb5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131ce4a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8136bf9d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8141ce55)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814e0693)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc7f5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff817643a3)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff81877e74)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff8195fe88)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810c605a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8115efe9)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e1a45)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811fe6c5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132fc8a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8138415c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff81436ca5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814f9ac3)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f003b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff81788393)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff818a9ca4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81997026)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810cde36)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8117035e)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff81200eb1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff81225e2d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81369b12)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff813ce3fd)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff81486f4d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/secid.c (ffffffff81505ca5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In block/genhd.c (ffffffff8155a979)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8184e1d4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff8197a206)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81a6f3c1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810c8908)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8116ce92)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff81200281)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff812233cb)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376e16)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff813e002d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff814a456d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/secid.c (ffffffff81522df5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In drivers/scsi/sg.c (ffffffff8185e784)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff8197e844)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81a77daa)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810ca3a8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8116daf2)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff81200c31)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff81227e7b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d92c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff813e6bdd)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff814aa53c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/secid.c (ffffffff81528fe5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In drivers/scsi/sg.c (ffffffff81840f04)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff81962694)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81a6395f)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810dd1f8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff811933cf)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff812329a1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff8126016b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca86c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8143877d)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff81502a08)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/apparmor/secid.c (ffffffff81587385)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - security/apparmor/secid.c:aa_alloc_secid
```
```
In drivers/scsi/sg.c (ffffffff818cdbbd)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff81a098d4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81b1ccb7)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810f6ae1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff811c4699)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff81275d70)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff812aaa1b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451c98)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff814b3287)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff81593f81)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In drivers/scsi/sg.c (ffffffff81a1bd62)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff81b71216)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81ca0ee4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff811191c1)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb07cb)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff812cbe90)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff8130a26b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0a08)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff81549ef7)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8163cb41)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In drivers/scsi/sg.c (ffffffff81b9cf22)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff81d0e026)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81e5cf24)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff81126691)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff836d57bb)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff812f3800)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff8133977b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815172b8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff81581b17)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff81675051)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In drivers/scsi/sg.c (ffffffff81bf3502)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/md/dm.c (ffffffff81d77626)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81eb9acc)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff81130c81)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff83907b2b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
```
```
In kernel/bpf/syscall.c (ffffffff81312690)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff8135f8ab)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b6a8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
```
```
In fs/kernfs/dir.c (ffffffff815ba5b7)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff816b1411)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In drivers/scsi/sg.c (ffffffff81c48e21)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b44e)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_alloc
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9d4dd)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb11b6)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
```
```
In drivers/md/dm.c (ffffffff81e2e856)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81f7ccd6)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffff8000101246fc)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffff8000101d1a78)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffff800010264aa8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffff800010285698)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ed044)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
```
In fs/kernfs/dir.c (ffff800010452730)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffff80001051d2a4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffff8000105fb57c)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/scsi/sg.c (ffff80001099173c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffff800010aff91c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffff800010c43fec)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (c037784c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (c04135c4)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (c0496c90)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (c04b5c74)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (c05c3990)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/kernfs/dir.c (c0614c88)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (c06d96e4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (c07a65c8)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/scsi/sg.c (c0a61b5c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (c0bde5d0)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (c0d54c44)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (c00000000016e3a0)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (c00000000023a0b0)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (c0000000003094c4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (c0000000003304f0)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f4074)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/kernfs/dir.c (c00000000056a854)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (c000000000666348)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (c000000000794740)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/scsi/sg.c (c000000000a52dd4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (c000000000beb53c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (c000000000d3f548)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffe0000dc6fc)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffe00014a30e)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe0001a06e6)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffe0001baaca)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0bd8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/kernfs/dir.c (ffffffe0002e526c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffe000384bdc)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffe0004376ca)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/scsi/sg.c (ffffffe0005f38c8)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffe0006f017c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffe0007b2584)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810c03da)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff81157609)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811da065)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f6ce5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132826a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8137c73c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8142f285)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814f20a3)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b582b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff8173ca83)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff8184fb24)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81936e96)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810aebe4)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff8114a929)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811cce25)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811e9a35)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318e0a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8136d20c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8141fd05)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814e25d3)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169346b)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff8171e723)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff81817134)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff818f0996)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810bf92a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff811553d9)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d7e35)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811f4ab5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325d3a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8137a20c)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8142b425)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff814ee133)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3cfb)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff8177d213)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff8189f154)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff81988026)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In kernel/pid.c (ffffffff810c7d41)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup.c (ffffffff811628f9)
Location: include/linux/idr.h:172
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e61d5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff81202fc5)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337b96)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
```
In fs/kernfs/dir.c (ffffffff8138d284)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - fs/kernfs/dir.c:__kernfs_new_node
```
```
In ipc/util.c (ffffffff8144237a)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In block/genhd.c (ffffffff815071b3)
Location: include/linux/idr.h:172
Inline: True
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe3a9)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
```
```
In drivers/scsi/sg.c (ffffffff81797045)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/md/dm.c (ffffffff818ba26e)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
```
```
In net/sched/cls_api.c (ffffffff819aa28e)
Location: include/linux/idr.h:172
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
</details>
</li>
</ul>

## Differences
