# Function: <code>get_files_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a530)
Location: fs/file.c:417
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8122a530-ffffffff8122a570: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252c80)
Location: fs/file.c:418
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81252c80-ffffffff81252cc0: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265ef0)
Location: fs/file.c:418
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81265ef0-ffffffff81265f30: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812736d0)
Location: fs/file.c:404
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812736d0-ffffffff81273710: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296000)
Location: fs/file.c:405
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81296000-ffffffff81296040: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc4c0)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812bc4c0-ffffffff812bc500: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1780)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812d1780-ffffffff812d17c0: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee780)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812ee780-ffffffff812ee7c0: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300240)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81300240-ffffffff81300280: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813393b0)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff813393b0-ffffffff813393f0: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1d00)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffff8000103b1d00-ffff8000103b1db0: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591244)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
c0591244-c05912a8: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ad9f0)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
c0000000004ad9f0-c0000000004adab8: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000275eda)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffe000275eda-ffffffe000275f52: get_files_struct (STB_GLOBAL)
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
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8820)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812f8820-ffffffff812f8860: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9440)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812e9440-ffffffff812e9480: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6630)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812f6630-ffffffff812f6670: get_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct files_struct *get_files_struct(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307850)
Location: fs/file.c:400
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81307850-ffffffff81307893: get_files_struct (STB_GLOBAL)
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
