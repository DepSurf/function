# Function: <code>dir_emit_dot</code>

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
In fs/libfs.c (ffffffff8123496f)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:empty_dir_readdir
```
```
In fs/proc/base.c (ffffffff8127dfde)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/generic.c (ffffffff8127f7be)
Location: include/linux/fs.h:3019
Inline: True
```
```
In fs/proc/fd.c (ffffffff81281660)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812837b0)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81285262)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81289ce0)
Location: include/linux/fs.h:3019
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff812f859e)
Location: include/linux/fs.h:3019
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
In fs/libfs.c (ffffffff8125d450)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812ab66a)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812ac800)
Location: include/linux/fs.h:3168
Inline: True
```
```
In fs/proc/fd.c (ffffffff812ae729)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812b0a51)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812b23d3)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812b713c)
Location: include/linux/fs.h:3168
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff8132c18e)
Location: include/linux/fs.h:3168
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
In fs/libfs.c (ffffffff81270980)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812c0d4a)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812c20f0)
Location: include/linux/fs.h:3138
Inline: True
```
```
In fs/proc/fd.c (ffffffff812c4109)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812c6441)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812c7bf3)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812cc94c)
Location: include/linux/fs.h:3138
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/fat/dir.c (ffffffff81341ece)
Location: include/linux/fs.h:3138
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
In fs/libfs.c (ffffffff8127de03)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812cdeeb)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812cf338)
Location: include/linux/fs.h:3308
Inline: True
```
```
In fs/proc/fd.c (ffffffff812d13a8)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812d34d6)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4f57)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812d9dbc)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff812df390)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813566cf)
Location: include/linux/fs.h:3308
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
In fs/libfs.c (ffffffff812a08e3)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff812f273b)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff812f3aa8)
Location: include/linux/fs.h:3388
Inline: True
```
```
In fs/proc/fd.c (ffffffff812f5b97)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff812f7d06)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff812f9787)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff812fe6d3)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81303d00)
Location: include/linux/fs.h:3388
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8137b2fe)
Location: include/linux/fs.h:3388
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
In fs/libfs.c (ffffffff812c7473)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8131f5cb)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81320b48)
Location: include/linux/fs.h:3415
Inline: True
```
```
In fs/proc/fd.c (ffffffff81323417)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81325109)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81326e36)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8132ca23)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81332b70)
Location: include/linux/fs.h:3415
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813a9bd9)
Location: include/linux/fs.h:3415
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
In fs/libfs.c (ffffffff812dc5a3)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813366fb)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81337c48)
Location: include/linux/fs.h:3494
Inline: True
```
```
In fs/proc/fd.c (ffffffff8133a337)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8133c1f9)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8133e006)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813439b3)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81349f60)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813c29b9)
Location: include/linux/fs.h:3494
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
In fs/libfs.c (ffffffff812fac63)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135e7ab)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8135fdb8)
Location: include/linux/fs.h:3505
Inline: True
```
```
In fs/proc/fd.c (ffffffff813624d7)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81364444)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81365ee7)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136badd)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81371920)
Location: include/linux/fs.h:3505
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ed22d)
Location: include/linux/fs.h:3505
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
In fs/libfs.c (ffffffff8130c973)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81376a0b)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81378018)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffff8137a737)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8137c6d4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e177)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81383cad)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81389d60)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8140734d)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffff81346aa0)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813bf917)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813c11b0)
Location: include/linux/fs.h:3617
Inline: True
```
```
In fs/proc/fd.c (ffffffff813c3ccf)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813c5eed)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8aa6)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813cec73)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813d5113)
Location: include/linux/fs.h:3617
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81454fc3)
Location: include/linux/fs.h:3617
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
In fs/libfs.c (ffffffff81352f90)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d17a1)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d30a0)
Location: include/linux/fs.h:3414
Inline: True
```
```
In fs/proc/fd.c (ffffffff813d5a34)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813d7e8d)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813daa96)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e08a3)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813e6e33)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81471473)
Location: include/linux/fs.h:3414
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
In fs/libfs.c (ffffffff81359680)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff813d8697)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813d9dea)
Location: include/linux/fs.h:3667
Inline: True
```
```
In fs/proc/fd.c (ffffffff813dc936)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff813ded3c)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff813e16a8)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff813e73d2)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813ee432)
Location: include/linux/fs.h:3667
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff81476dc5)
Location: include/linux/fs.h:3667
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
In fs/libfs.c (ffffffff813a7b20)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff81429dc7)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8142b51a)
Location: include/linux/fs.h:3647
Inline: True
```
```
In fs/proc/fd.c (ffffffff8142e016)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff814306ec)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8143318d)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81438f95)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81440352)
Location: include/linux/fs.h:3647
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814ce466)
Location: include/linux/fs.h:3647
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
In fs/libfs.c (ffffffff8142c442)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff814a324a)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff814a4c39)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff814a7cdb)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff814aa3eb)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff814acfef)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff814b40bb)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff814baa74)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8155ac9d)
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b9da2)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815384ca)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8153a169)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff8153d20b)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff8153fff6)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8154343f)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8154aeab)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81552344)
Location: include/linux/fs.h:3569
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff815fba29)
Location: include/linux/fs.h:3569
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
In fs/libfs.c (ffffffff814eed02)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8157070d)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81572409)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815754de)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff815786d9)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff8157b895)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81582b02)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8158a090)
Location: include/linux/fs.h:3184
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff816339b5)
Location: include/linux/fs.h:3184
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
In fs/libfs.c (ffffffff81522db2)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:offset_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff815a8fd7)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff815aadb9)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
```
```
In fs/proc/fd.c (ffffffff815ade3c)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff815b0e09)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff815b4145)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff815bb732)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff815c2d63)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff8166ce85)
Location: include/linux/fs.h:3481
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
```
In fs/tracefs/event_inode.c (ffffffff816ab4cd)
Location: include/linux/fs.h:3481
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
In fs/libfs.c (ffff8000103c180c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffff80001044205c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffff800010443f9c)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffff8000104469e4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffff800010449054)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffff80001044b684)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffff80001045298c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffff80001045b998)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffff8000104e6110)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (c059e4c4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c0607848)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c060910c)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (c060bb9c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c060e158)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c060fe90)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c061518c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c061bdb4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c06a5724)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (c0000000004c08c0)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (c000000000557598)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (c000000000559708)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (c00000000055ca44)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (c00000000055f8f4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (c0000000005626c8)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (c00000000056afc0)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (c000000000575714)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (c000000000623f08)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffe0002816ae)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffe0002d8d7c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffe0002da1c6)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffe0002dc960)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffe0002de872)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0a92)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffe0002e539e)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffe0002ebf04)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffe000358b76)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffff81304f53)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136efeb)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813705f8)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffff81372d17)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81374cb4)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81376757)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8137c28d)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81382340)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813ff92d)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffff812f5b73)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8135fa7b)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff81361088)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffff813637e7)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81365784)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81367227)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8136cd5d)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff81372dd0)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813f03ad)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffff81302d43)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8136cabb)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff8136e0c8)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffff813707e7)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81372784)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81374227)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff81379d5d)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff8137fe10)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff813fccad)
Location: include/linux/fs.h:3567
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
In fs/libfs.c (ffffffff813143c3)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/libfs.c:empty_dir_readdir
  - fs/libfs.c:dcache_readdir
```
```
In fs/proc/base.c (ffffffff8138039c)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/generic.c (ffffffff813819f8)
Location: include/linux/fs.h:3567
Inline: True
```
```
In fs/proc/fd.c (ffffffff813841b7)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/namespaces.c (ffffffff81386164)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_sysctl.c (ffffffff81387c24)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
```
In fs/kernfs/dir.c (ffffffff8138d69d)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
```
```
In fs/configfs/dir.c (ffffffff813936c0)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_readdir
```
```
In fs/fat/dir.c (ffffffff814128cd)
Location: include/linux/fs.h:3567
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:__fat_readdir
```
</details>
</li>
</ul>

## Differences
