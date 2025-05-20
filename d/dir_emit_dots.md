# Function: <code>dir_emit_dots</code>

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
In fs/libfs.c (ffffffff8123481c)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:empty_dir_readdir
```
```
In fs/proc/base.c (ffffffff8127df3e)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/generic.c (ffffffff8127f725)
Location: include/linux/fs.h:3029
Inline: True
```
```
In fs/proc/fd.c (ffffffff8128157a)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812836f7)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812850f6)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81289b8f)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff812f877b)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8125d433)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812ab4c8)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812ac765)
Location: include/linux/fs.h:3178
Inline: True
```
```
In fs/proc/fd.c (ffffffff812ae63a)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812b09a7)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812b2216)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812b6fdc)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff8132c36e)
Location: include/linux/fs.h:3178
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81270963)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812c0ba8)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812c2055)
Location: include/linux/fs.h:3148
Inline: True
```
```
In fs/proc/fd.c (ffffffff812c401a)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812c6397)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812c7a96)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812cc7ec)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff813420ae)
Location: include/linux/fs.h:3148
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8127ddf3)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812cded8)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812cf325)
Location: include/linux/fs.h:3318
Inline: True
```
```
In fs/proc/fd.c (ffffffff812d139a)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812d34c8)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4f49)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812d9daf)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff812df370)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8135670e)
Location: include/linux/fs.h:3318
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812a08d3)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812f2728)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812f3a95)
Location: include/linux/fs.h:3398
Inline: True
```
```
In fs/proc/fd.c (ffffffff812f5b8a)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812f7cf8)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812f9779)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812fe6bc)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81303ce0)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8137b341)
Location: include/linux/fs.h:3398
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812c7455)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8131f5c2)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81320b25)
Location: include/linux/fs.h:3425
Inline: True
```
```
In fs/proc/fd.c (ffffffff8132340a)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813250fb)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81326e28)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8132c8d6)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81332b67)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813a9de0)
Location: include/linux/fs.h:3425
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812dc585)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813366f2)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81337c25)
Location: include/linux/fs.h:3504
Inline: True
```
```
In fs/proc/fd.c (ffffffff8133a32a)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8133c1eb)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8133dff8)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81343866)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81349f57)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813c2bc0)
Location: include/linux/fs.h:3504
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812fac45)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135e7a2)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8135fd95)
Location: include/linux/fs.h:3515
Inline: True
```
```
In fs/proc/fd.c (ffffffff813624ca)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81364437)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81365eda)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136bad4)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81371917)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ed400)
Location: include/linux/fs.h:3515
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8130c955)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81376a02)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81377ff5)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffff8137a72a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8137c6c7)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e16a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81383ca4)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81389d57)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81407520)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81346a75)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813bf753)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813c1175)
Location: include/linux/fs.h:3627
Inline: True
```
```
In fs/proc/fd.c (ffffffff813c3bb8)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813c5e37)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813c88b4)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813ceb13)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813d4fc7)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81455197)
Location: include/linux/fs.h:3627
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81352f65)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d15d3)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d3065)
Location: include/linux/fs.h:3424
Inline: True
```
```
In fs/proc/fd.c (ffffffff813d5957)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813d7dd7)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813da8a4)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e0743)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813e6ce7)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81471640)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81359655)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d84d2)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d9d55)
Location: include/linux/fs.h:3677
Inline: True
```
```
In fs/proc/fd.c (ffffffff813dc857)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813dec87)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813e1484)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e7273)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813ee2e7)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81476e46)
Location: include/linux/fs.h:3677
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff813a7af5)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81429c02)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8142b485)
Location: include/linux/fs.h:3657
Inline: True
```
```
In fs/proc/fd.c (ffffffff8142df37)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81430637)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81432f5c)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81438e28)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81440207)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814ce584)
Location: include/linux/fs.h:3657
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8142c405)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff814a3073)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff814a4b85)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff814a7bbe)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff814aa328)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814ace28)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff814b3f28)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff814ba917)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8155ace4)
Location: include/linux/fs.h:3429
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff814b9d65)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815382f3)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8153a0b5)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff8153d0ee)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8153ff38)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81543278)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8154ad18)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815521e7)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff815fbb35)
Location: include/linux/fs.h:3579
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff814eecc5)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81570536)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81572355)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815753c1)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8157861b)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b6cb)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8158296c)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81589f2a)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81633ac7)
Location: include/linux/fs.h:3194
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81522d75)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:offset_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815a8ed5)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff815aad05)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815add12)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff815b0d4b)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff815b3f7b)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff815bb59c)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815c2bfd)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8166cf97)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/tracefs/event_inode.c (ffffffff816ab320)
Location: include/linux/fs.h:3491
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_iterate
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
In fs/libfs.c (ffff8000103c1804)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffff800010442054)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffff800010443f94)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffff8000104469dc)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffff80001044904c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffff80001044b67c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffff800010452988)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffff80001045b98c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffff8000104e62ac)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (c059e4b0)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c060783c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c06090f4)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (c060bb88)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c060e14c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c060fe84)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c0615188)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c061bdb0)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c06a5b2c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (c0000000004c08ac)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c000000000557588)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c0000000005596ec)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (c00000000055ca38)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c00000000055f8e8)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c0000000005626bc)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c00000000056afb8)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c000000000575710)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c000000000624374)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffe0002816aa)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffe0002d8d76)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffe0002da1be)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffe0002dc95a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffe0002de86c)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0a8e)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffe0002e5392)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffe0002ebeec)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffe000358e2a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81304f35)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136efe2)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813705d5)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffff81372d0a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81374ca7)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137674a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8137c284)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81382337)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ffb00)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812f5b55)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135fa72)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81361065)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffff813637da)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81365777)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8136721a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136cd54)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81372dc7)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813f0580)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81302d25)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136cab2)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8136e0a5)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffff813707da)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81372777)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137421a)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81379d54)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137fe07)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813fce80)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff813143a5)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81380393)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813819d5)
Location: include/linux/fs.h:3577
Inline: True
```
```
In fs/proc/fd.c (ffffffff813841aa)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81386157)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81387c16)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8138d694)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813936b7)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81412aaa)
Location: include/linux/fs.h:3577
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
```
</details>
</li>
</ul>

## Differences
