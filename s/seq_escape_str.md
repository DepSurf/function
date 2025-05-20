# Function: <code>seq_escape_str</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2c2a)
Location: include/linux/seq_file.h:132
Inline: True
Inline callers:
  - fs/seq_file.c:seq_escape
```
```
In fs/proc/array.c (ffffffff8142c529)
Location: include/linux/seq_file.h:132
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
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
In kernel/cgroup/cgroup.c (ffffffff811c2ba1)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cfca2)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8144d32d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/proc/array.c (ffffffff814a5d4d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/ext4/super.c (ffffffff81524113)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff815c54bb)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
```
In lib/dynamic_debug.c (ffffffff817605df)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_proc_show
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
In kernel/cgroup/cgroup.c (ffffffff81206ec1)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812136a2)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff814db8fd)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/proc/array.c (ffffffff8153b36d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/ext4/super.c (ffffffff815c1789)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816720d9)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
```
In lib/dynamic_debug.c (ffffffff8188cebe)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_proc_show
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
In kernel/cgroup/cgroup.c (ffffffff8121c4a1)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228fb2)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8150fe9d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/proc/array.c (ffffffff8157369d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/ext4/super.c (ffffffff815f8ef1)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816aa624)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
```
In lib/dynamic_debug.c (ffffffff818cf42e)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_proc_show
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
In kernel/cgroup/cgroup.c (ffffffff81232efc)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240e02)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
```
```
In fs/proc_namespace.c (ffffffff8154434d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
```
```
In fs/proc/array.c (ffffffff815ac04d)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/proc/array.c:proc_task_name
```
```
In fs/ext4/super.c (ffffffff81631a7b)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
```
```
In security/selinux/hooks.c (ffffffff816e75c4)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - security/selinux/hooks.c:show_sid
```
```
In lib/dynamic_debug.c (ffffffff81921282)
Location: include/linux/seq_file.h:133
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_proc_show
```
</details>
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
