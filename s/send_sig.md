# Function: <code>send_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f300)
Location: kernel/signal.c:1429
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - kernel/auditsc.c:audit_log_exit
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_tee
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8108f300-ffffffff8108f331: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092370)
Location: kernel/signal.c:1429
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_to_pipe
  - fs/fuse/dev.c:fuse_dev_splice_read
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81092370-ffffffff810923a1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097300)
Location: kernel/signal.c:1435
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81097300-ffffffff81097331: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094600)
Location: kernel/signal.c:1457
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81094600-ffffffff81094631: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b4a0)
Location: kernel/signal.c:1458
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8109b4a0-ffffffff8109b4d1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f3f0)
Location: kernel/signal.c:1456
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:generic_file_write_iter
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8109f3f0-ffffffff8109f421: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a76b0)
Location: kernel/signal.c:1543
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810a76b0-ffffffff810a76e1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810addb0)
Location: kernel/signal.c:1612
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810addb0-ffffffff810adde1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b43d0)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810b43d0-ffffffff810b4401: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc920)
Location: kernel/signal.c:1613
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - mm/filemap.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:wait_for_space
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wqe_worker_send_sig
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810bc920-ffffffff810bc951: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7c30)
Location: kernel/signal.c:1614
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - fs/io-wq.c:io_wq_worker_cancel
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810b7c30-ffffffff810b7c61: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9190)
Location: kernel/signal.c:1616
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810b9190-ffffffff810b91c1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb720)
Location: kernel/signal.c:1642
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810cb720-ffffffff810cb751: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e26b0)
Location: kernel/signal.c:1643
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810e26b0-ffffffff810e26ff: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102ab0)
Location: kernel/signal.c:1644
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81102ab0-ffffffff81102aff: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110ecf0)
Location: kernel/signal.c:1650
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8110ecf0-ffffffff8110ed3f: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118670)
Location: kernel/signal.c:1656
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/read_write.c:generic_write_check_limits
  - fs/exec.c:exec_binprm
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff81118670-ffffffff811186bf: send_sig (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110420)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:uprobe_notify_resume
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffff800010110420-ffff800010110480: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367e00)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - arch/arm/kernel/traps.c:arm_syscall
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - mm/filemap.c:generic_write_check_limits
  - fs/exec.c:__do_execve_file
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - fs/binfmt_flat.c:calc_reloc
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
c0367e00-c0367e40: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157ba0)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
c000000000157ba0-c000000000157bd8: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d034c)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - fs/exec.c:__do_execve_file
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - fs/binfmt_flat.c:calc_reloc
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffe0000d034c-ffffffe0000d0396: send_sig (STB_GLOBAL)
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
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae740)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810ae740-ffffffff810ae771: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d090)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff8109d090-ffffffff8109d0c1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adca0)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810adca0-ffffffff810adcd1: send_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct *p, int priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5f00)
Location: kernel/signal.c:1617
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep
  - arch/x86/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/events/uprobes.c:handle_swbp
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
  - net/core/stream.c:sk_stream_error
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
```
**Symbols:**

```
ffffffff810b5f00-ffffffff810b5f31: send_sig (STB_GLOBAL)
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
