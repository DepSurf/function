# Function: <code>dir_emit_dotdot</code>

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
In fs/libfs.c (ffffffff812349b3)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:empty_dir_readdir
```
```
In fs/proc/base.c (ffffffff8127e014)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/generic.c (ffffffff8127f7f6)
Location: include/linux/fs.h:3024
Inline: True
```
```
In fs/proc/fd.c (ffffffff81281698)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812837ec)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8128529a)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81289d14)
Location: include/linux/fs.h:3024
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff812f853c)
Location: include/linux/fs.h:3024
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
In fs/libfs.c (ffffffff8125d486)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812ab6ab)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812ac838)
Location: include/linux/fs.h:3173
Inline: True
```
```
In fs/proc/fd.c (ffffffff812ae75e)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812b0a8d)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812b240f)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812b7170)
Location: include/linux/fs.h:3173
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff8132c12c)
Location: include/linux/fs.h:3173
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
In fs/libfs.c (ffffffff812709b6)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812c0d8b)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812c2128)
Location: include/linux/fs.h:3143
Inline: True
```
```
In fs/proc/fd.c (ffffffff812c413e)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812c647d)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812c7c2f)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812cc980)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff81341e6c)
Location: include/linux/fs.h:3143
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
In fs/libfs.c (ffffffff8127de39)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812cdf27)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812cf374)
Location: include/linux/fs.h:3313
Inline: True
```
```
In fs/proc/fd.c (ffffffff812d13e4)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812d3512)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4f93)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812d9df4)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff812df3c5)
Location: include/linux/fs.h:3313
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8135675c)
Location: include/linux/fs.h:3313
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
In fs/libfs.c (ffffffff812a091f)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812f277b)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812f3ae9)
Location: include/linux/fs.h:3393
Inline: True
```
```
In fs/proc/fd.c (ffffffff812f5bd6)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812f7d47)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812f97c8)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812fe70a)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81303d3c)
Location: include/linux/fs.h:3393
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8137b393)
Location: include/linux/fs.h:3393
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
In fs/libfs.c (ffffffff812c74af)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8131f60a)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81320b88)
Location: include/linux/fs.h:3420
Inline: True
```
```
In fs/proc/fd.c (ffffffff81323456)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81325152)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81326e77)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8132ca56)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81332ba8)
Location: include/linux/fs.h:3420
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813a9d69)
Location: include/linux/fs.h:3420
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
In fs/libfs.c (ffffffff812dc5df)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8133673a)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81337c87)
Location: include/linux/fs.h:3499
Inline: True
```
```
In fs/proc/fd.c (ffffffff8133a376)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8133c242)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8133e047)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813439e6)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81349f98)
Location: include/linux/fs.h:3499
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813c2b49)
Location: include/linux/fs.h:3499
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
In fs/libfs.c (ffffffff812fac9f)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135e7ea)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8135fdf7)
Location: include/linux/fs.h:3510
Inline: True
```
```
In fs/proc/fd.c (ffffffff81362516)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81364483)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81365f26)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136bb15)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81371958)
Location: include/linux/fs.h:3510
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ed397)
Location: include/linux/fs.h:3510
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
In fs/libfs.c (ffffffff8130c9af)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81376a4a)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81378057)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffff8137a776)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8137c713)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e1b6)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81383ce5)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81389d98)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814074b7)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffff81346adc)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813bf956)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813c11ec)
Location: include/linux/fs.h:3622
Inline: True
```
```
In fs/proc/fd.c (ffffffff813c3d0a)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813c5f28)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8ae7)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813ceca6)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813d514b)
Location: include/linux/fs.h:3622
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81455119)
Location: include/linux/fs.h:3622
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
In fs/libfs.c (ffffffff81352fcc)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d17e0)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d30dc)
Location: include/linux/fs.h:3419
Inline: True
```
```
In fs/proc/fd.c (ffffffff813d5a6f)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813d7ec8)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813daad7)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e08d6)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813e6e6b)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814715c2)
Location: include/linux/fs.h:3419
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
In fs/libfs.c (ffffffff813596bc)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d86d6)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d9e25)
Location: include/linux/fs.h:3672
Inline: True
```
```
In fs/proc/fd.c (ffffffff813dc971)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813ded77)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813e16e9)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e7405)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813ee46a)
Location: include/linux/fs.h:3672
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81476c7e)
Location: include/linux/fs.h:3672
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
In fs/libfs.c (ffffffff813a7b5c)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81429e06)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8142b555)
Location: include/linux/fs.h:3652
Inline: True
```
```
In fs/proc/fd.c (ffffffff8142e051)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81430727)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814331cc)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81438fc8)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8144038a)
Location: include/linux/fs.h:3652
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814ce504)
Location: include/linux/fs.h:3652
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
In fs/libfs.c (ffffffff8142c47e)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff814a3289)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff814a4c79)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff814a7d1c)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff814aa42e)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814ad034)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff814b40f3)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff814baaab)
Location: include/linux/fs.h:3424
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8155ae18)
Location: include/linux/fs.h:3424
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
In fs/libfs.c (ffffffff814b9dde)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81538509)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8153a1a9)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff8153d24c)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8154003b)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81543484)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8154aee4)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8155237b)
Location: include/linux/fs.h:3574
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff815fbab9)
Location: include/linux/fs.h:3574
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
In fs/libfs.c (ffffffff814eed44)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81570752)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8157244f)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff81575525)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81578724)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b8dd)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81582b3f)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8158a0cb)
Location: include/linux/fs.h:3189
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81633a4b)
Location: include/linux/fs.h:3189
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
In fs/libfs.c (ffffffff81522df4)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:offset_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815a9018)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff815aadff)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815ade83)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff815b0e54)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff815b418d)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff815bb76f)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815c2d9e)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8166cf1b)
Location: include/linux/fs.h:3486
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/tracefs/event_inode.c (ffffffff816ab50f)
Location: include/linux/fs.h:3486
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
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffff8000104420a0)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffff800010443fdc)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffff800010446a24)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffff800010449094)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffff80001044b6c8)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffff8000104529c4)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffff80001045b9d4)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffff8000104e6238)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (c059e514)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c0607898)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c060915c)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (c060bbec)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c060e1a8)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c060fee0)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c06151d8)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c061be04)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c06a59ec)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (c0000000004c0910)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c0000000005575e0)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c00000000055974c)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (c00000000055ca88)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c00000000055f938)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c00000000056270c)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c00000000056b000)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c000000000575764)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c0000000006241d8)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffe0002816d2)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffe0002d8da4)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffe0002da1ea)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffe0002dc986)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffe0002de898)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0ab8)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffe0002e53c4)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffe0002ebf2e)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffe000358aa6)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffff81304f8f)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136f02a)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81370637)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffff81372d56)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81374cf3)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81376796)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8137c2c5)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81382378)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ffa97)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffff812f5baf)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135faba)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813610c7)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffff81363826)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813657c3)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81367266)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136cd95)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81372e08)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813f0517)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffff81302d7f)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136cafa)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8136e107)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffff81370826)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813727c3)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81374266)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81379d95)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137fe48)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813fce17)
Location: include/linux/fs.h:3572
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
In fs/libfs.c (ffffffff813143ff)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813803db)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81381a37)
Location: include/linux/fs.h:3572
Inline: True
```
```
In fs/proc/fd.c (ffffffff813841f6)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813861a3)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81387c65)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8138d6d5)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813936f7)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81412a35)
Location: include/linux/fs.h:3572
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
</details>
</li>
</ul>

## Differences
