# Function: <code>copy_user_generic</code>

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
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a50c)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ac0f)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c715)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103db16)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/signal.c (ffffffff81091084)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In mm/maccess.c (ffffffff8119153b)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_write
```
```
In mm/memory.c (ffffffff811bc8e9)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In fs/readdir.c (ffffffff81220722)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81220c89)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff8126401d)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/compat_ioctl.c (ffffffff812661cd)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81321c4a)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81322174)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff813e592c)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff813f78ee)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f7a27)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
```
```
In lib/iov_iter.c (ffffffff813fb981)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff815c2704)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a41d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a56b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b6e2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c480)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d958)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/signal.c (ffffffff81094163)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In mm/maccess.c (ffffffff811a5dcf)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811d7657)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812481e2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81248913)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812901ce)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/compat_ioctl.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81356fd8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813574ef)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff8142bc1b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e788)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8143e8d5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
```
```
In lib/iov_iter.c (ffffffff814446a8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8161b173)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/dumpstack_64.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039d0d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039e5a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103af82)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bd10)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d248)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/signal.c (ffffffff81099142)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8115e7ac)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In mm/maccess.c (ffffffff811b614f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811e735e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff8125b212)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8125b943)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812a520e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/compat_ioctl.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8136d44f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8136d9df)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/pstore/platform.c (ffffffff8136ba8f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_write_buf_user_compat
```
```
In block/compat_ioctl.c (ffffffff81445a1b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b800)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:_copy_from_user
  - arch/x86/lib/usercopy.c:_copy_to_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8145b925)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
```
```
In lib/iov_iter.c (ffffffff81462821)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8164bde9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81037c1f)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037d75)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038e37)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff81039d24)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103b2a4)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/signal.c (ffffffff810963e8)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811619dc)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
```
```
In mm/maccess.c (ffffffff811be09c)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff811f24a0)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff81267c08)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81268790)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat_ioctl.c (ffffffff812b4307)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff812b71be)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ba1c8)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff812c5a39)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In block/compat_ioctl.c (ffffffff81454816)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff81464eb4)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8146c645)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9c40)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816607ea)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/usb/core/devio.c (ffffffff816c02f1)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff817afd9c)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff817fa3c9)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4d5)
Location: arch/x86/include/asm/uaccess_64.h:27
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039ecf)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a025)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b377)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c724)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103dcd4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/signal.c (ffffffff8109d17e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8116e25c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In mm/maccess.c (ffffffff811d2d5d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81209464)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff8128a4b8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8128b040)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat_ioctl.c (ffffffff812d7a32)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff812daa63)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ddaab)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff812e98e9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In block/compat_ioctl.c (ffffffff814804a9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff81490e31)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81498961)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e7a6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816c9d0a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/usb/core/devio.c (ffffffff8172bd21)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81827f19)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff81877d1a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81984fb5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103abda)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b537)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c894)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103dc87)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103f26a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8117d26c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In mm/maccess.c (ffffffff811f40dd)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8122a372)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812b0878)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812b1a6f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In fs/compat_ioctl.c (ffffffff81301be6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff8130363d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81306d2b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff8131681e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814b5013)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff814c6215)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814cdbb6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81554334)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8170668e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8176b16e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81870c31)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818c98fa)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff819e14a4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c0da)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ca5c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ddb4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f257)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104086a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118aadc)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8120646d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8123d9b6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812c5a32)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812c8fd3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff813175c3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff81318d3a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c498)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff8132d7ce)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814c88d3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff814da975)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814e2486)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bd8f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81728a7e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8178f6fe)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff81891da7)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818f47d1)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c454)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ee84)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f0ab)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810405ca)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104182b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81042f19)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119872a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8121d75d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8124f660)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812e24c4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e370f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In fs/compat_ioctl.c (ffffffff8133f472)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81340666)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81343d3f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff8135550e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814f70d9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
```
In lib/iov_iter.c (ffffffff81506171)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8150e341)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c067)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8176415b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817cd8f3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818dbd01)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff819542ee)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c103)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f594)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f714)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d9a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041fab)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043679)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a401a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122b1ee)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125dbef)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812f3f7d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f73cb)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff813576b2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff81358bb6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c132)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff8136d84e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff8151559e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff815241a1)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8152c191)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd667)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8178814b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817fe339)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff8190e85b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8198a7fa)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac33c3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042744)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a44)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043ff0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044b3c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81046f03)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In kernel/trace/trace.c (ffffffff811bd44a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812580db)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8128d2fd)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff8132fff2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/quota/compat.c (ffffffff813b5349)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
```
```
In lib/iov_iter.c (ffffffff8158975d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/usercopy.c (ffffffff8158fb5d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff906)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666871)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/usb/core/devio.c (ffffffff818ce747)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff819e0512)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042714)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104298b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043e71)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81046753)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811bb05a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812627ed)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812982df)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff8133b947)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff815a4368)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff815ac6a8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8162179d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff816236a5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81624836)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In net/socket.c (ffffffff819dd8e3)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
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
In arch/x86/kernel/fpu/regset.c (ffffffff810440f4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104436c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045b71)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81048169)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811be842)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8126724d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8129d92f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff81341e3c)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff815ad95a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff815b7347)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8160509d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606f55)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81608226)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In net/socket.c (ffffffff819c5ad5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
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
In arch/x86/kernel/fpu/regset.c (ffffffff8104a496)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a807)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/tls.c (ffffffff8104ea79)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff811e90f6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812a3c8d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff812ddfc4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff8138f7fc)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff81614e9f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff8161d977)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8167398a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff81675a68)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e66)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/kernel/fpu/regset.c (ffffffff81054658)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054cae)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/tls.c (ffffffff81059c73)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff81220dc1)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812fbd34)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff8133e054)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff81410801)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff816e2de0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff816eb3ba)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8178df9a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff817906e8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff81791e0b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
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
In arch/x86/kernel/fpu/regset.c (ffffffff81062268)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106280e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/tls.c (ffffffff81067623)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff8126bc61)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff81365f14)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813b7170)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In fs/select.c (ffffffff8149b4d1)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff817d55e5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff817dba7a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8204b7ca)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204e2f8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fc2e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
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
In arch/x86/kernel/fpu/regset.c (ffffffff810632eb)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106436c)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff81068eb5)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff81282fc1)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8139837b)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff813e98fb)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In fs/select.c (ffffffff814d0785)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff81810229)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8181ae19)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff820ca0aa)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccb8f)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce156)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
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
In arch/x86/kernel/fpu/regset.c (ffffffff8106a5eb)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b842)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff8107032b)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In kernel/trace/trace.c (ffffffff8129e351)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff813c219b)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/memory.c (ffffffff814148f1)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In fs/select.c (ffffffff815030c1)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff8185837f)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff81860189)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff821a4a12)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a73bf)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8986)
Location: arch/x86/include/asm/uaccess_64.h:105
Inline: True
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f714)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f894)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040f1a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104212b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff810437f9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119c63a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8122383e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff8125623f)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812ec55d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef9ab)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff8134fc92)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff81351196)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81354712)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff81365e2e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff8150db7e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff8151c781)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81524771)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b17b7)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8173c83b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817b6719)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ae85b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8192a66a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81a62213)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ef14)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f094)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810306fa)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff810317eb)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81032e19)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118f6b4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812169ee)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff812488d8)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812dd18d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e05db)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff81340972)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff81341e76)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813453d2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff81356ace)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff814fdfae)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff8150ca71)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81514a51)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0947)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8171e4db)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817a8139)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818687ab)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff818e441a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f283)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f554)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f6d4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d5a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041f6b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043639)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119a40a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff812215de)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81253fdf)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812ea36d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ed7bb)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff8134d762)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff8134ec66)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813521e2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff813638fe)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff81509c0e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff81518811)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81520801)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1d47)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8177cfcb)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817f31b9)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff818ff85b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8197b7fa)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace603)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
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
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81040834)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810409c4)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104213a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104334b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81044a39)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a80aa)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In mm/maccess.c (ffffffff8123079e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (ffffffff81263a34)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In fs/readdir.c (ffffffff812fb35d)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fe7c5)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat_ioctl.c (ffffffff81360ce2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/binfmt_elf.c (ffffffff813621e6)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813659a2)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/quota/compat.c (ffffffff81376fae)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In block/compat_ioctl.c (ffffffff8152327e)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/iov_iter.c (ffffffff81531fd1)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8153a181)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb7b7)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81796dfb)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8180d439)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In net/socket.c (ffffffff8192084b)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff8199dd4a)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/usercopy.c (ffffffff81adab13)
Location: arch/x86/include/asm/uaccess_64.h:28
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
</ul>

## Differences
