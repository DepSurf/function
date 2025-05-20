# Function: <code>sigismember</code>

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
In arch/x86/entry/common.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100484e)
Location: include/linux/signal.h:58
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/signal.c (ffffffff8108ddd6)
Location: include/linux/signal.h:58
Inline: True
Inline callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/sched/wait.c (ffffffff81820bcf)
Location: include/linux/signal.h:58
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io_timeout
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/proc/array.c (ffffffff8128098e)
Location: include/linux/signal.h:58
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/signal.h:58
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff814e80b6)
Location: include/linux/signal.h:58
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:is_ignored
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:58
Inline: True
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
In arch/x86/entry/common.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004bb4)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/signal.c (ffffffff81093662)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/sched/core.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/sched/wait.c (ffffffff8189b1cd)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
```
```
In kernel/sched/swait.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/proc/array.c (ffffffff812ad9f7)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815319fd)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:73
Inline: True
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
In arch/x86/entry/common.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004c30)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/signal.c (ffffffff810985f2)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/sched/core.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/sched/wait.c (ffffffff818cf748)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_wait_io_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:bit_wait_io
  - kernel/sched/wait.c:bit_wait
```
```
In kernel/sched/swait.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/vmscan.c (ffffffff811c8c2a)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/proc/array.c (ffffffff812c32e8)
Location: include/linux/signal.h:73
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8155e13d)
Location: include/linux/signal.h:73
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:73
Inline: True
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
In arch/x86/entry/common.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004aad)
Location: include/linux/signal.h:51
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/signal.c (ffffffff810958b4)
Location: include/linux/signal.h:51
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/sched/core.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81906b88)
Location: include/linux/signal.h:51
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/vmscan.c (ffffffff811d12df)
Location: include/linux/signal.h:51
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/proc/array.c (ffffffff812d0568)
Location: include/linux/signal.h:51
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/signal.h:51
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157cf1c)
Location: include/linux/signal.h:51
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:51
Inline: True
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
In arch/x86/entry/common.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004d1b)
Location: include/linux/signal.h:66
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/signal.c (ffffffff8109c713)
Location: include/linux/signal.h:66
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/sched/core.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81990bf8)
Location: include/linux/signal.h:66
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:atomic_t_wait
```
```
In kernel/sched/swait.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/vmscan.c (ffffffff811e67af)
Location: include/linux/signal.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/proc/array.c (ffffffff812f4da8)
Location: include/linux/signal.h:66
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/signal.h:66
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e184c)
Location: include/linux/signal.h:66
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:66
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003944)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810053cb)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8107637b)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/ptrace.c (ffffffff8109a730)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810a0b68)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff819ec6c4)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810d95d7)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff819ed4dd)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810d9bcd)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/seccomp.c (ffffffff8116b63a)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811e621b)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/vmscan.c (ffffffff81207c75)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff81220919)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In mm/memcontrol.c (ffffffff81281c16)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/userfaultfd.c (ffffffff812f15e9)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/coredump.c (ffffffff8130c964)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff8130ea95)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/proc/array.c (ffffffff813221cf)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813444ad)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In security/selinux/hooks.c (ffffffff813fae78)
Location: include/linux/signal.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:68
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161ab00)
Location: include/linux/signal.h:68
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:68
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003e04)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810052cb)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8107c648)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81094b96)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/ptrace.c (ffffffff810a296b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810a900b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81a27715)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810e30b3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a2870d)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810e36e3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff81178f8d)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f6d6b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff8121a7f5)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff81233969)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81305fa9)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff81322299)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap.c (ffffffff81325371)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff813392df)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff8135c5fd)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8141745f)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81637d70)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003d74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005357)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8107fba8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810998a1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a75fe)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810aedf1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81a984ec)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810e9dc1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a98f17)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ea3f2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff81185e3b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120eb31)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff8122a1e5)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff81243d2e)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b0072)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81327836)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff81349f38)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134c2b5)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff81361979)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813858c7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81445031)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166c014)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003d74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810053d7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff81080c38)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a0003)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810adc18)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b5408)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81acfe37)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810f5791)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ad0867)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f5dc2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81159245)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff811919f3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121c171)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff81238065)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff812521ee)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffff812855a6)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c1ae2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8133a616)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff813621d8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff81364585)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff81379bd9)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff8139e317)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145eba1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffff81513ab5)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168e684)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81005552)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810062c0)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff81087c58)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a6d0d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810b56f8)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bdc69)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/sched/core.c (ffffffff81bc862e)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ff01c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81bc913d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ff5a8)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81bc9294)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81bca407)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81bca638)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
```
```
In kernel/locking/rwsem.c (ffffffff8110ef64)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8116a021)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (ffffffff8118565d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff811a6888)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b568f)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81248801)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8124e58d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff8125acce)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812670fd)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81284752)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81289e6c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812adf8b)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812b76c4)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812caef3)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff812fb54e)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81308fc0)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81310ed4)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (ffffffff8131d9b3)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/ioctl.c (ffffffff8132b975)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (ffffffff8135a7f4)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8136e41b)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff8137392c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff81386072)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_flush
```
```
In fs/dax.c (ffffffff8138ca09)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff8139602a)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/coredump.c (ffffffff813a7aec)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/coredump.c:coredump_finish
```
```
In fs/iomap/buffered-io.c (ffffffff813abe7d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff813c2c99)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff813dbde0)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813ea1b2)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81409386)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81411ad2)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81457806)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81463464)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814b5c8d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8151f237)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff8154f0c7)
Location: include/linux/signal.h:80
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156a43a)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff81574c48)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81632e02)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740934)
Location: include/linux/signal.h:80
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176f289)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8182a8fb)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81977bcd)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005358)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff81088378)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a2935)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810b08f8)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810b8f7b)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c4141e)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810fd87c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c41f62)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810fe113)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c41ffc)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c43091)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c434f6)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110c067)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/entry/common.c (ffffffff8113b45f)
Location: include/linux/signal.h:80
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81166761)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (ffffffff81182768)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff811a3e98)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2f6d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81252f11)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81258b7d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff81264e56)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81271b4d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff8128ea63)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81293b64)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812b99c5)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff812c2608)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812d6b10)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff813073ab)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff81314de2)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81329688)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/ioctl.c (ffffffff81336f35)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/remap_range.c (ffffffff81366383)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff813677f5)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8137b863)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff8138180f)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io_uring.c (ffffffff81397552)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_flush
```
```
In fs/dax.c (ffffffff8139e199)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813a7d4a)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/coredump.c (ffffffff813b898c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/coredump.c:coredump_finish
```
```
In fs/iomap/buffered-io.c (ffffffff813bd34d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff813d4e29)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff813ed708)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff813fc58c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff8141b88d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff81424f82)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81473bc6)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ecb1)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814d396d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8153c0be)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff8156cdbe)
Location: include/linux/signal.h:80
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81584e9c)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_blkg
```
```
In block/blk-iocost.c (ffffffff81591b4e)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff81657f52)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175c864)
Location: include/linux/signal.h:80
Inline: True
```
```
In drivers/char/mem.c (ffffffff81789c69)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b31e)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff8197c85d)
Location: include/linux/signal.h:80
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100542d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff81088f7d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a35ac)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810b1eae)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810bab6a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff81c33391)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ffc5c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81c33ed2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff811004f3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81c33f6c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81c34753)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81c35545)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8110de9b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/entry/common.c (ffffffff8113c746)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81167501)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (ffffffff811838c8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff811a4c15)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811b37fd)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81257251)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8125d081)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/page-writeback.c (ffffffff81269087)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81276e3d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff812940f3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81299501)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff812c21ba)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff812c948e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812ddc1d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8130db21)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8131b524)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8132f498)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/ioctl.c (ffffffff8133d095)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/remap_range.c (ffffffff8136cd8a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8136e235)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff81381fe3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81388a8c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff813a5262)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
```
In fs/verity/enable.c (ffffffff813aedac)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff813b06cc)
Location: include/linux/signal.h:82
Inline: True
```
```
In fs/coredump.c (ffffffff813c014c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff813c449d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff813dbc59)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff813f3d84)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff81402e11)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81421dba)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (ffffffff8142bc86)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81479612)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81484841)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff814da3ed)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815447ae)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff81574c5e)
Location: include/linux/signal.h:82
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158db18)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81598996)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff8163a772)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817406f4)
Location: include/linux/signal.h:82
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176d4d6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e5d2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890318)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff819606ed)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005a4f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff810983c2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b4ed6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810c4369)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810cd3f7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_join_group_stop
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff81d51cd9)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff8111bd41)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81d5286a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff8111c55a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (ffffffff81d52908)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81d52f8b)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81d53d41)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8112d670)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/rtmutex_api.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/entry/common.c (ffffffff8115f866)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8118d07e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8119bc16)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/pid_namespace.c (ffffffff811ab9a8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff811ce355)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff811dd5cd)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/uprobes.c (ffffffff81292fe1)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff81298fc4)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/oom_kill.c (ffffffff812a3837)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812a5a8a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff812b473d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab_node
```
```
In mm/compaction.c (ffffffff812d4682)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff812d9e4b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (ffffffff81305b40)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (ffffffff8130e4b5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81324e7c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff81358a59)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff813684fb)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff8137cc78)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff813bba4a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff813bd304)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff813cf249)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff813d5db1)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/io-wq.c (ffffffff813f17ae)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
```
```
In fs/dax.c (ffffffff813f4a31)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff813fe94c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff814002b9)
Location: include/linux/signal.h:82
Inline: True
```
```
In fs/coredump.c (ffffffff8140ff7c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff81413aeb)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff8142d2e9)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff81445e73)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8145553b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814744d8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8147fb26)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff814d0c18)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbec1)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff815332ed)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff815a4f4e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff815d91ae)
Location: include/linux/signal.h:82
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815f3587)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81600187)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (ffffffff816ab387)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c114c)
Location: include/linux/signal.h:82
Inline: True
```
```
In drivers/char/mem.c (ffffffff817f2e66)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8a74)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923f0c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff81a0838d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004c02)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff810ab01a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810c9ab4)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810daae6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff810e54f3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff81f2223c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8113fb72)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:__wait_for_common
```
```
In kernel/locking/mutex.c (ffffffff81f2480c)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24d9e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f258d1)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f264fd)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/entry/common.c (ffffffff81189dd7)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811bc2db)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff811cbe76)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/pid_namespace.c (ffffffff811dd11a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff81202591)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8121434b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/irq_work.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e8a4e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff812ef8a5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
```
```
In mm/oom_kill.c (ffffffff812fb77f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff812fe752)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff8131079d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff81333636)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff81339b71)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff813607c7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81371d86)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff813777e3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8139360b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff813d2905)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff813e5cf2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff813fbfe4)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff81441c61)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff81443538)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff81457ffb)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff8145e2fa)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff81468093)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81472495)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81474114)
Location: include/linux/signal.h:82
Inline: True
```
```
In fs/coredump.c (ffffffff8148592e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8148b408)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff814a6c1a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff814c20f2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff814d2de3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff814f64db)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff81502baa)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff8155d7a5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81569b86)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff815c5667)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8164bb99)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff8168bd78)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll
```
```
In block/blk-cgroup.c (ffffffff816a4b0f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff816b2762)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff816da892)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff817ce470)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fdaea)
Location: include/linux/signal.h:82
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2a29)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a798a6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
```
```
In drivers/md/dm.c (ffffffff81b70724)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005672)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff810c4d0a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e7114)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff810fabf6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff81105b45)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff820ccae8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8116a752)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (ffffffff820cfc12)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d041a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff820d12b7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d1fda)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/entry/common.c (ffffffff811c62e7)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811fe50b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8120f356)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/pid_namespace.c (ffffffff81222ada)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff8124a3d8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8125de5b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/irq_work.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813527ae)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8135a605)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff81365897)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff81368e1c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff81383e0d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff813aa32d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813b35cf)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/gup.c:get_dump_page
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff813e2bb8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ef566)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff813f501a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81411d77)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff814580c0)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff8146d79c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81485094)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff814d0f41)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff814d2ae8)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff814e734b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff814edf89)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff814f840f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81503fb3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815063a5)
Location: include/linux/signal.h:82
Inline: True
```
```
In fs/coredump.c (ffffffff815190f7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8151f47b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff8153c26a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff8155a355)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff8156b9e9)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff81590894)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff8159d6aa)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff815ff7f5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d7d2)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff81672257)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff81704d99)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff81741c51)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_classic
```
```
In block/blk-cgroup.c (ffffffff8176389f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff81771c9c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff817a6982)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff818edf20)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a5725f)
Location: include/linux/signal.h:82
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7084a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81d0d79d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004ebc)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff810c83d3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810f2bc6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff81106d76)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff81111dd5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:unhandled_signal
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff82150e6d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff8117ae62)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (ffffffff82153469)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff821547aa)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff8215561c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff821563ff)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/entry/common.c (ffffffff811d8f07)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/kexec_core.c (ffffffff812137f3)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff81224d66)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/pid_namespace.c (ffffffff8123913a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff812616cb)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff812750cb)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/irq_work.c (0)
Location: include/linux/signal.h:82
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813839be)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff8138bf27)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff81397d37)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff8139afbc)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813b58bd)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff813dd5d6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff813e2c8f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff814176d7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814230d7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff814283a7)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff814450ae)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/memcontrol.c (ffffffff8148de04)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814a226d)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ba014)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff81507a6f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff815093f5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8151db9b)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff8152446c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff8152fc0c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff8153ba2f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8153d6e3)
Location: include/linux/signal.h:82
Inline: True
```
```
In fs/coredump.c (ffffffff815509f5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8155755a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/array.c (ffffffff8157458a)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff81592126)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815a3899)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815c7a47)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/ext4/namei.c (ffffffff815d3ef6)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff816377d5)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff81645689)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff816aa79c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8173efb9)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff8177d28f)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817a293e)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817b1117)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff817e7900)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff81931400)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa183f)
Location: include/linux/signal.h:82
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3f8c)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81d766b1)
Location: include/linux/signal.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810077cc)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff810d0abb)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810fb742)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (ffffffff811106c6)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/ptrace.c:ptrace_unfreeze_traced
```
```
In kernel/signal.c (ffffffff8111b775)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:send_sig_perf
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:ptrace_trap_notify
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:unhandled_signal
```
```
In kernel/workqueue.c (0)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/sched/core.c (ffffffff82233c82)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/build_utility.c (ffffffff81188872)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:bit_wait_io_timeout
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:bit_wait_io
  - kernel/sched/build_utility.c:bit_wait
  - kernel/sched/build_utility.c:prepare_to_swait_event
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (ffffffff822362a9)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff822375ea)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:___down_common
```
```
In kernel/locking/rwsem.c (ffffffff8223845c)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (0)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223923f)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/entry/common.c (ffffffff811eee87)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/kexec_core.c (ffffffff8122b723)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8123ca56)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_kill
```
```
In kernel/pid_namespace.c (ffffffff81252e0a)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (ffffffff8127b8cb)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f9f2)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/irq_work.c (0)
Location: include/linux/signal.h:83
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ace1e)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (ffffffff813b5a98)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:folio_wait_bit_common
```
```
In mm/oom_kill.c (ffffffff813c1b67)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page-writeback.c (ffffffff813c4f00)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (ffffffff813de8ad)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:drop_slab
```
```
In mm/compaction.c (ffffffff81407536)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/gup.c (ffffffff8140d4cf)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/vmalloc.c (ffffffff814441e7)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81450007)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
```
```
In mm/madvise.c (ffffffff81461bce)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff814bd786)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (ffffffff814d3659)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ec590)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
```
```
In fs/remap_range.c (ffffffff8153c1f4)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
```
```
In fs/buffer.c (ffffffff8153e315)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
```
```
In fs/eventpoll.c (ffffffff8155217b)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/userfaultfd.c (ffffffff81558c99)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/dax.c (ffffffff81564aec)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
```
```
In fs/verity/enable.c (ffffffff81570d0c)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff81572b40)
Location: include/linux/signal.h:83
Inline: True
```
```
In fs/coredump.c (ffffffff81586886)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:dump_interrupted
```
```
In fs/iomap/buffered-io.c (ffffffff8158da65)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff8159bf70)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In fs/proc/array.c (ffffffff815acf3a)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (ffffffff815cae96)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (ffffffff815dc6d9)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (ffffffff815f9673)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_interrupted
```
```
In fs/ext4/namei.c (ffffffff8160c566)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (ffffffff81670cc5)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (ffffffff8167eb7a)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (ffffffff816e77ef)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (ffffffff8177fe39)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (ffffffff817bf61f)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - block/blk-mq.c:blk_hctx_poll
```
```
In block/blk-cgroup.c (ffffffff817e6482)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (ffffffff817f4f27)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io-wq.c (ffffffff8182d70e)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In drivers/pci/vpd.c (ffffffff81979f20)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_read
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af429f)
Location: include/linux/signal.h:83
Inline: True
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c1889b)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In drivers/md/dm.c (ffffffff81e2d8e1)
Location: include/linux/signal.h:83
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/arm64/kernel/ptrace.c (ffff80001008ee40)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm64/kernel/sys_compat.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In arch/arm64/mm/fault.c (ffff800010da92f4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (ffff8000100f4600)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffff800010107c40)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffff8000101115a4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffff800010da1b6c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffff8000101583a8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffff800010da27c4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffff80001015946c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffff8000101c87f8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffff8000102093c0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffff8000102a7af8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffff8000102c8e20)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffff8000102ea074)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffff80001031f658)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffff80001036367c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffff8000103f96ac)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffff8000104287f0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042b804)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffff800010445dd0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffff800010471928)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffff8000105541b0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffff800010617f04)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fde0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/arm/kernel/ptrace.c (c030cffc)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
```
In arch/arm/kernel/traps.c (c030fb7c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:arm_syscall
```
```
In arch/arm/mm/fault.c (c0e9fa44)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
```
In kernel/fork.c (c0352d8c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/ptrace.c (c0362800)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/signal.c (c0368c4c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (c0e99b84)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (c03a5f54)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c0e9a880)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c03a6964)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (c0e9aae4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
```
```
In kernel/locking/mutex.c (c0e9c6f4)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (c0e9cd50)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_killable
```
```
In kernel/locking/rwsem.c (c03b5e40)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/kexec_core.c (c040f770)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (c0427e40)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/seccomp.c (c04480ec)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (c04572ac)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (c04d6bfc)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In mm/filemap.c (c04db990)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
```
```
In mm/page-writeback.c (c04e8678)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
```
```
In mm/vmscan.c (c04f7304)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (c05115f0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_unlock_should_abort
```
```
In mm/gup.c (c0514ad0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/page_alloc.c (c0534d64)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
```
In mm/madvise.c (c0537cb0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (c0559d4c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (c05642f8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c056ac80)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
```
In fs/exec.c (c0575128)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings
```
```
In fs/ioctl.c (c058330c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/buffer.c (c05b603c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/buffer.c:cont_write_begin
```
```
In fs/eventpoll.c (c05c68a4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/userfaultfd.c (c05cb54c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/verity/enable.c (c05dd9b4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/coredump.c (c05f1554)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c05f43f8)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (c060af30)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (c0623698)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/fsmap.c (c06328c4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (c06558a8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
```
```
In fs/ext4/namei.c (c065efa4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/fat/fatent.c (c06a7f78)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/ecryptfs/read_write.c (c06b41e8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/selinux/hooks.c (c0707384)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (c07666ac)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In block/blk-mq.c (c079b418)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (c07b91a8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
```
In block/blk-iocost.c (c07c3220)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (c088b9d0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/tty/tty_jobctrl.c (c0967140)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (c09a7764)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/md/dm.c (c0bdec14)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_prepare_ioctl
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
In arch/powerpc/kernel/ptrace.c (c0000000000194b0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/powerpc/mm/fault.c (c000000000086a90)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In kernel/fork.c (c00000000013a8ec)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (c00000000014ef74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (c000000000158f9c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (c000000000ee2c68)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (c0000000001ad000)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (c000000000ee3db0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (c0000000001ad9e0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (c000000000231000)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (c00000000028644c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (c00000000035b194)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (c0000000003850a0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (c0000000003ac1fc)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (c0000000003f4520)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (c000000000450550)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (c000000000501b90)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (c000000000538acc)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c00000000053ca00)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (c00000000055b960)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (c0000000005922e0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (c0000000006a42f0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (c0000000007b76c4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff3cc)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b6394)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
```
In arch/riscv/mm/fault.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/fork.c (ffffffe0000c0bee)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffe0000cc61a)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/signal.c (ffffffe0000d0e74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffe0008c523e)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffe0000fed7a)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffe0008c5cb4)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffe0000ff48e)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffe00016b772)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e8340)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffe0001fe9ce)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffe000220df0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffe000242d44)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffe0002a89c6)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffe0002c6a32)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffe0002c908e)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffe0002dbe04)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffe0002fda8c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffe0003a97ea)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffe00044e49a)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000538008)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003d74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810053d7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8107fc38)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81099923)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a7f88)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810af778)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81a6eca7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810eeb91)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a6f6d7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ef1c2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81151865)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff8118a013)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812147c1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff812306b5)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff8124a83e)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffff8127dbf6)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ba0c2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81332bf6)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8135a7b8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135cb65)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff813721b9)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813968f7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81457181)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150c095)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654104)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81002254)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003ab7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8106ec9b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff81088369)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff81096948)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff8109e0b0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81a2b08b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810dec21)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81a2bb07)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810df242)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81144b45)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff8117d143)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120752b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff81223775)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff8123d7de)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffff8126faa3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ab352)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81323752)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8134b462)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8134d805)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff81362c89)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff81387387)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81447bbb)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffff814fc4cd)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816344e4)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003d74)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005397)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff8107fbe8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810998d3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810a74e8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_check_attach
```
```
In kernel/signal.c (ffffffff810aecd8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81adb0b7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810ebcc1)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81adbae7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810ec2f2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8114f715)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff81187de3)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81212561)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff8122e455)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff812485de)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffff8127b996)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b7ed2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813306c6)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff81358288)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8135a635)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff8136fc89)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff81394257)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81453221)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffff81508125)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816824c4)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/linux/signal.h:72
Inline: True
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
In arch/x86/entry/common.c (ffffffff81003e44)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810054f0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/mm/fault.c (ffffffff81081ce2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
```
In kernel/fork.c (ffffffff810a153c)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/ptrace.c (ffffffff810aedbf)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/signal.c (ffffffff810b6fd0)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:task_set_jobctl_pending
```
```
In kernel/sched/core.c (ffffffff81ae7573)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/wait.c (ffffffff810f6d21)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In kernel/sched/wait_bit.c (ffffffff81ae8087)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
```
```
In kernel/sched/swait.c (ffffffff810f7422)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/sched/swait.c:prepare_to_swait_event
```
```
In kernel/sched/completion.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/semaphore.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/locking/rwsem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8115c545)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/pid_namespace.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/seccomp.c (ffffffff81195737)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812214d8)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_deny_signal
```
```
In mm/filemap.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/vmscan.c (ffffffff8123d84b)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
```
```
In mm/compaction.c (ffffffff81257e0d)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/madvise.c (ffffffff8128b463)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c87c2)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/userfaultfd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81343014)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/coredump.c (ffffffff8136b9ba)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffff8136dd85)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/proc/array.c (ffffffff81383619)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
```
```
In fs/ext4/dir.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff813a82e7)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8146ad17)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
```
In crypto/api.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In block/blk-iocost.c (ffffffff8151f43d)
Location: include/linux/signal.h:72
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169cb0a)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/signal.h:72
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/signal.h:72
Inline: True
```
</details>
</li>
</ul>

## Differences
