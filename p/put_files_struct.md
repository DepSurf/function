# Function: <code>put_files_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a570)
Location: fs/file.c:430
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/file.c:reset_files_struct
  - fs/file.c:exit_files
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
```
**Symbols:**

```
ffffffff8122a570-ffffffff8122a63e: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252cc0)
Location: fs/file.c:431
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81252cc0-ffffffff81252dac: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265f30)
Location: fs/file.c:431
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81265f30-ffffffff8126601c: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81273710)
Location: fs/file.c:417
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/kcmp.c:SyS_kcmp
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81273710-ffffffff812737f3: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81296040)
Location: fs/file.c:418
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/kcmp.c:SyS_kcmp
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81296040-ffffffff8129612e: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bc500)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812bc500-ffffffff812bc5b8: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d17c0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812d17c0-ffffffff812d1878: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee7c0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812ee7c0-ffffffff812ee877: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300280)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff81300280-ffffffff81300337: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813393f0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/exec.c:__do_execve_file
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff813393f0-ffffffff813394bc: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345050)
Location: fs/file.c:415
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
  - fs/io_uring.c:io_req_clean_work
  - fs/io_uring.c:io_sq_thread_drop_mm_files
```
**Symbols:**

```
ffffffff81345050-ffffffff8134511c: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b3d0)
Location: fs/file.c:415
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff8134b3d0-ffffffff8134b49c: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399230)
Location: fs/file.c:415
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff81399230-ffffffff813992fc: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141bb70)
Location: fs/file.c:444
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff8141bb70-ffffffff8141bc5f: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a7cc0)
Location: fs/file.c:444
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff814a7cc0-ffffffff814a7daf: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dcca0)
Location: fs/file.c:444
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff814dcca0-ffffffff814dcd8f: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150f460)
Location: fs/file.c:444
Inline: True
Direct callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
**Symbols:**

```
ffffffff8150f460-ffffffff8150f54f: put_files_struct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b1db0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffff8000103b1db0-ffff8000103b1ec4: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c05912a8)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - fs/exec.c:__do_execve_file
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
c05912a8-c05913b0: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004adac0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
c0000000004adac0-c0000000004adc4c: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file.c (ffffffe00027609e)
Location: fs/file.c:413
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/exec.c:__do_execve_file
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffe000275226-ffffffe0002752f8: put_files_struct.part.0 (STB_LOCAL)
ffffffe000275f52-ffffffe000275f94: put_files_struct (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8860)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812f8860-ffffffff812f8917: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9480)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812e9480-ffffffff812e9537: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6670)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff812f6670-ffffffff812f6727: put_files_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_files_struct(struct files_struct *files);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813078a0)
Location: fs/file.c:413
Inline: True
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/coredump.c:do_coredump
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:seq_show
```
**Symbols:**

```
ffffffff813078a0-ffffffff81307952: put_files_struct (STB_GLOBAL)
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
