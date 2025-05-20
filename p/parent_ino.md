# Function: <code>parent_ino</code>

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
In fs/libfs.c (ffffffff812349b7)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:empty_dir_readdir
```
```
In fs/proc/base.c (ffffffff8127e017)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/generic.c (ffffffff8127f7fa)
Location: include/linux/fs.h:2892
Inline: True
```
```
In fs/proc/fd.c (ffffffff8128169c)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812837f0)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8128529e)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81289d14)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff812f8543)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8125d489)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812ab6ae)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812ac83c)
Location: include/linux/fs.h:3041
Inline: True
```
```
In fs/proc/fd.c (ffffffff812ae761)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812b0a91)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812b2413)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812b7170)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff8132c13a)
Location: include/linux/fs.h:3041
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812709b9)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812c0d8e)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812c212c)
Location: include/linux/fs.h:3011
Inline: True
```
```
In fs/proc/fd.c (ffffffff812c4141)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812c6481)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812c7c33)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812cc980)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff81341e7a)
Location: include/linux/fs.h:3011
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8127de3c)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812cdf2b)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812cf378)
Location: include/linux/fs.h:3181
Inline: True
```
```
In fs/proc/fd.c (ffffffff812d13e8)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812d3516)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4f97)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812d9df8)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff812df3c8)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8135676b)
Location: include/linux/fs.h:3181
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812a0922)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812f277f)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812f3aed)
Location: include/linux/fs.h:3261
Inline: True
```
```
In fs/proc/fd.c (ffffffff812f5bd9)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812f7d4b)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812f97cc)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812fe70d)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81303d3f)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8137b3a1)
Location: include/linux/fs.h:3261
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812c74b2)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8131f616)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81320b8c)
Location: include/linux/fs.h:3288
Inline: True
```
```
In fs/proc/fd.c (ffffffff81323459)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81325156)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81326e7b)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8132ca68)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81332bab)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813a9d70)
Location: include/linux/fs.h:3288
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812dc5e2)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81336746)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81337c8b)
Location: include/linux/fs.h:3367
Inline: True
```
```
In fs/proc/fd.c (ffffffff8133a379)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8133c246)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8133e04b)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813439f8)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81349f9b)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813c2b50)
Location: include/linux/fs.h:3367
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812faca2)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135e7f6)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8135fdfa)
Location: include/linux/fs.h:3378
Inline: True
```
```
In fs/proc/fd.c (ffffffff81362519)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8136448e)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81365f29)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136bb27)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137195b)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ed39e)
Location: include/linux/fs.h:3378
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8130c9b2)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81376a56)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8137805a)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffff8137a779)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8137c71e)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e1b9)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81383cf7)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81389d9b)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814074be)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81346adf)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813bf961)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813c11f0)
Location: include/linux/fs.h:3490
Inline: True
```
```
In fs/proc/fd.c (ffffffff813c3d0d)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813c5f33)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8af3)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813cecb8)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813d5156)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81455120)
Location: include/linux/fs.h:3490
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81352fcf)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d17eb)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d30e0)
Location: include/linux/fs.h:3287
Inline: True
```
```
In fs/proc/fd.c (ffffffff813d5a81)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813d7ed3)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813daae3)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e08e8)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813e6e76)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814715c9)
Location: include/linux/fs.h:3287
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff813596bf)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d86e1)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d9e28)
Location: include/linux/fs.h:3539
Inline: True
```
```
In fs/proc/fd.c (ffffffff813dc983)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813ded82)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813e16f5)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e7417)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813ee475)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81476c81)
Location: include/linux/fs.h:3539
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff813a7b5f)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81429e11)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8142b558)
Location: include/linux/fs.h:3519
Inline: True
```
```
In fs/proc/fd.c (ffffffff8142e063)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81430732)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814331cf)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81438fd3)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81440395)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814ce507)
Location: include/linux/fs.h:3519
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff8142c481)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff814a3295)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff814a4c7d)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff814a7d28)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff814aa439)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814ad03c)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff814b40ff)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff814baab6)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8155ae26)
Location: include/linux/fs.h:3297
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff814b9de1)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81538515)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8153a1ad)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff8153d258)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81540047)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8154348c)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8154aef0)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81552386)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff815fbac7)
Location: include/linux/fs.h:3439
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff814eed47)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8157075e)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81572453)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff81575531)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81578730)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b8e8)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81582b4b)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8158a0d7)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81633a59)
Location: include/linux/fs.h:3054
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81522df7)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:offset_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815a9025)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff815aae03)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815ade8f)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff815b0e60)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff815b4198)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff815bb77b)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815c2daa)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8166cf29)
Location: include/linux/fs.h:3351
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/tracefs/event_inode.c (ffffffff816ab512)
Location: include/linux/fs.h:3351
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
In fs/libfs.c (ffff8000103c1850)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffff8000104420a0)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffff800010443fdc)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffff800010446a24)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffff800010449094)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffff80001044b6c8)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffff8000104529c4)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffff80001045b9d4)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffff8000104e6238)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (c059e518)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c060789c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c0609160)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (c060bbf0)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c060e1ac)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c060fee4)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c06151e0)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c061be0c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c06a59f8)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (c0000000004c0914)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c0000000005575e4)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c000000000559750)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (c00000000055ca8c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c00000000055f93c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c000000000562710)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c00000000056b00c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c000000000575770)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c0000000006241dc)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffe0002816d6)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffe0002d8da8)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffe0002da1ec)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffe0002dc98a)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffe0002de89c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0abc)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffe0002e53c4)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffe0002ebf2e)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffe000358aa6)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81304f92)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136f036)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8137063a)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffff81372d59)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81374cfe)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81376799)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8137c2d7)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8138237b)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ffa9e)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff812f5bb2)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135fac6)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813610ca)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffff81363829)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813657ce)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81367269)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136cda7)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81372e0b)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813f051e)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81302d82)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136cb06)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8136e10a)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffff81370829)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813727ce)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81374269)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81379da7)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137fe4b)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813fce1e)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
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
In fs/libfs.c (ffffffff81314402)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813803e6)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81381a3a)
Location: include/linux/fs.h:3440
Inline: True
```
```
In fs/proc/fd.c (ffffffff813841f9)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813861ae)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81387c69)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8138d6e0)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81393702)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81412a3c)
Location: include/linux/fs.h:3440
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
</details>
</li>
</ul>

## Differences
