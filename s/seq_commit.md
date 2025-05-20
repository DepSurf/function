# Function: <code>seq_commit</code>

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
In fs/seq_file.c (ffffffff812314f8)
Location: include/linux/seq_file.h:88
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
```
```
In fs/proc/array.c (ffffffff81280aea)
Location: include/linux/seq_file.h:88
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/sysfs/file.c (ffffffff8128c7d6)
Location: include/linux/seq_file.h:88
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff81259be8)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff812adb57)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/sysfs/file.c (ffffffff812b9e66)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff8126d3b8)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff812c3450)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/sysfs/file.c (ffffffff812cf593)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff8127ab16)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff812d06b5)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/sysfs/file.c (ffffffff812dcd2b)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff8129d586)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff812f4efe)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/sysfs/file.c (ffffffff81301640)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff812c376f)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff81321372)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff8132f38b)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff812d89bf)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff81338482)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff81346748)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff814c21dc)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff812f6ddd)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff81360b3a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff8136ea66)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f08e6)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff81308e1d)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff81378d9a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff81386d76)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff81509cca)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff8134215a)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff813c1e33)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff813d18c8)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff8156ab8c)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff8134e81a)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff813d3f86)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff813e3618)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff815855e8)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff81354b7a)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff813dadb5)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff813ea248)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff8158c1df)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff813a2f89)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
```
```
In fs/sysfs/file.c (ffffffff8143bfc8)
Location: include/linux/seq_file.h:83
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff81426cf3)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
```
```
In fs/sysfs/file.c (ffffffff81e7b3d9)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff814b3793)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
```
```
In fs/sysfs/file.c (ffffffff8154e8e4)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffffffff814e87fd)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
```
```
In fs/sysfs/file.c (ffffffff815865ae)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/namespace.c (ffffffff81512e86)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/namespace.c:statmount_string
```
```
In fs/seq_file.c (ffffffff8151c68d)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem
  - fs/seq_file.c:seq_escape_mem
```
```
In fs/sysfs/file.c (ffffffff815bf08e)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
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
In fs/seq_file.c (ffff8000103bc898)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffff8000104452b8)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffff800010456a34)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffff80001060cb20)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (c059a40c)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (c060a18c)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (c0618a68)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (c07b76cc)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (c0000000004ba100)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (c00000000055ab94)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (c000000000570aa8)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (c0000000007a9b90)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffe00027df8a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffe0002db252)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffe0002e8130)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffe00044573c)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff813013fd)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff8137137a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff8137f356)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff815022aa)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff812f201d)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff81361e0a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff8136fde6)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff814f27ea)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff812ff1ed)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff8136ee4a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff8137ce26)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff814fe33a)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
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
In fs/seq_file.c (ffffffff8131052d)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_dentry
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path_root
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_path
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape_mem_ascii
  - fs/seq_file.c:seq_escape
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff813827da)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/sysfs/file.c (ffffffff81390906)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_kf_seq_show
  - fs/sysfs/file.c:sysfs_kf_seq_show
```
```
In block/blk-cgroup.c (ffffffff815173c0)
Location: include/linux/seq_file.h:84
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
```
</details>
</li>
</ul>

## Differences
