# Function: <code>fget_task</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339930)
Location: fs/file.c:763
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
```
**Symbols:**

```
ffffffff81339930-ffffffff81339988: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345560)
Location: fs/file.c:863
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff81345560-ffffffff813455b8: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b900)
Location: fs/file.c:875
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff8134b900-ffffffff8134b958: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399740)
Location: fs/file.c:935
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff81399740-ffffffff81399798: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c0a0)
Location: fs/file.c:937
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff8141c0a0-ffffffff8141c158: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a81f0)
Location: fs/file.c:937
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff814a81f0-ffffffff814a82a8: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dd1d0)
Location: fs/file.c:938
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff814dd1d0-ffffffff814dd288: fget_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *fget_task(struct task_struct *task, unsigned int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150fb10)
Location: fs/file.c:1060
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_fd_link
```
**Symbols:**

```
ffffffff8150fb10-ffffffff8150fbc1: fget_task (STB_GLOBAL)
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
