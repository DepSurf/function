# Function: <code>task_lookup_fd_rcu</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813455c0)
Location: fs/file.c:875
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:kcmp_epoll_target
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813455c0-ffffffff81345625: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b960)
Location: fs/file.c:887
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8134b960-ffffffff8134b9c5: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813997a0)
Location: fs/file.c:947
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff813997a0-ffffffff81399805: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c160)
Location: fs/file.c:949
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8141c160-ffffffff8141c1d0: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a82c0)
Location: fs/file.c:949
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff814a82c0-ffffffff814a8330: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *task_lookup_fd_rcu(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd2a0)
Location: fs/file.c:950
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff814dd2a0-ffffffff814dd310: task_lookup_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
