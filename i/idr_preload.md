# Function: <code>idr_preload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813e9e00)
Location: lib/idr.c:395
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff813e9e00-ffffffff813e9e95: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff814301e0)
Location: lib/idr.c:395
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814301e0-ffffffff81430275: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144c410)
Location: lib/idr.c:395
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8144c410-ffffffff8144c4a5: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0520)
Location: lib/radix-tree.c:2104
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818f0520-ffffffff818f0534: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976970)
Location: lib/radix-tree.c:2101
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff81976970-ffffffff81976984: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3120)
Location: lib/radix-tree.c:2102
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/sched/act_api.c:tcf_idr_create
```
**Symbols:**

```
ffffffff819d3120-ffffffff819d3134: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cb10)
Location: lib/radix-tree.c:1491
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_create
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a0cb10-ffffffff81a0cb24: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c4a0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a7c4a0-ffffffff81a7c4b4: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab37d0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81ab37d0-ffffffff81ab37e4: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815edb10)
Location: lib/radix-tree.c:1470
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff815edb10-ffffffff815edb24: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612240)
Location: lib/radix-tree.c:1470
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81612240-ffffffff81612254: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5930)
Location: lib/radix-tree.c:1471
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff815f5930-ffffffff815f5944: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662d90)
Location: lib/radix-tree.c:1471
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - security/apparmor/secid.c:aa_alloc_secid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81662d90-ffffffff81662da4: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d090)
Location: lib/radix-tree.c:1471
Inline: True
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff8177d090-ffffffff8177d0b5: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82039910)
Location: lib/radix-tree.c:1471
Inline: True
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff82039910-ffffffff82039935: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7c30)
Location: lib/radix-tree.c:1469
Inline: True
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff820b7c30-ffffffff820b7c55: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82192540)
Location: lib/radix-tree.c:1469
Inline: True
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_alloc_id
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_alloc
  - drivers/gpu/drm/drm_drv.c:drm_minor_alloc
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff82192540-ffffffff82192565: idr_preload (STB_GLOBAL)
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
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e6f8)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010d8e6f8-ffff800010d8e714: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e888fc)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c0e888fc-c0e88918: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecf920)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c000000000ecf920-c000000000ecf954: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6730)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffe0008b6730-ffffffe0008b674c: idr_preload (STB_GLOBAL)
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
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52620)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a52620-ffffffff81a52634: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f720)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a0f720-ffffffff81a0f734: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abea10)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81abea10-ffffffff81abea24: idr_preload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void idr_preload(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acaed0)
Location: lib/radix-tree.c:1478
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/kernfs/dir.c:__kernfs_new_node
  - ipc/util.c:ipc_addid
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_id
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm.c:alloc_dev
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81acaed0-ffffffff81acaeeb: idr_preload (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
