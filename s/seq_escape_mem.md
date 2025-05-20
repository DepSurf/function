# Function: <code>seq_escape_mem</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file *m, const char *src, size_t len, unsigned int flags, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2ba0)
Location: fs/seq_file.c:374
Inline: False
Direct callers:
  - fs/seq_file.c:seq_escape
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff813a2ba0-ffffffff813a2c0c: seq_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file *m, const char *src, size_t len, unsigned int flags, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81426920)
Location: fs/seq_file.c:374
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc/array.c:proc_task_name
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff81426920-ffffffff8142699d: seq_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file *m, const char *src, size_t len, unsigned int flags, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3370)
Location: fs/seq_file.c:374
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc/array.c:proc_task_name
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff814b3370-ffffffff814b33ed: seq_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file *m, const char *src, size_t len, unsigned int flags, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e83c0)
Location: fs/seq_file.c:374
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc/array.c:proc_task_name
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff814e83c0-ffffffff814e8447: seq_escape_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seq_escape_mem(struct seq_file *m, const char *src, size_t len, unsigned int flags, const char *esc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c250)
Location: fs/seq_file.c:374
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc/array.c:proc_task_name
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - lib/dynamic_debug.c:ddebug_proc_show
```
**Symbols:**

```
ffffffff8151c250-ffffffff8151c2d7: seq_escape_mem (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
