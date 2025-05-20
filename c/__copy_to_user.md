# Function: <code>__copy_to_user</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e806)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a50c)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ac0f)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c715)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d9f2)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810784c1)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81091084)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff810937d0)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In fs/readdir.c (ffffffff81220722)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81220c89)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff8126401d)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/compat_ioctl.c (ffffffff812661cd)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81321c4a)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81322174)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff813e5c43)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff813fbee1)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff815c2704)
Location: arch/x86/include/asm/uaccess_64.h:145
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff8102d7b0)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a296)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103abe5)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b563)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c471)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d82d)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079c52)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff81094163)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff810969fd)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In fs/readdir.c (ffffffff812481d2)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812488f8)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812901be)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/binfmt_elf.c (ffffffff81356fd8)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813574ef)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff8142c04a)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff8144498a)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8161b14d)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff8102d637)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039b86)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a485)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ae03)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bd01)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d11d)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107da22)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff81099142)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109b9ad)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In fs/readdir.c (ffffffff8125b202)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8125b928)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812a51fe)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/binfmt_elf.c (ffffffff8136d44f)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8136d9df)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff81445e4a)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b706)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:_copy_to_user
```
```
In lib/iov_iter.c (ffffffff81463145)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8164bdc6)
Location: arch/x86/include/asm/uaccess_64.h:179
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff8102b87d)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81037ab5)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81038315)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038ce4)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff81039d17)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103b191)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c20b)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810963e8)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109879d)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In fs/readdir.c (ffffffff81267bf8)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81268778)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/binfmt_elf.c (ffffffff812b71a7)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ba1ad)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff816607ca)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/kernel/signal.c (ffffffff8102c5a3)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039d65)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a597)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103a7ae)
Location: include/linux/uaccess.h:100
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c717)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103dbc1)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108290b)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff8109d17e)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109f47d)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In fs/readdir.c (ffffffff8128a4a8)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8128b028)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/binfmt_elf.c (ffffffff812daa63)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ddaab)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff816c9cea)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/kernel/signal.c (ffffffff8102d8aa)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ac62)
Location: include/linux/uaccess.h:100
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b9ba)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103bcb6)
Location: include/linux/uaccess.h:100
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103dc6c)
Location: include/linux/uaccess.h:100
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103f168)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085fcb)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812b0868)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812b1a62)
Location: include/linux/uaccess.h:100
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8130363d)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81306d2b)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff8170667e)
Location: include/linux/uaccess.h:100
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff8102eaf8)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c162)
Location: include/linux/uaccess.h:97
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ceca)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103da2a)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f23c)
Location: include/linux/uaccess.h:97
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104075f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cd5e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812c5a1e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812c8fbc)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81318d3a)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c498)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff81728a6e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff81030700)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ed1f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103eeda)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fa43)
Location: include/linux/uaccess.h:97
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041826)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81042e0f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090c3b)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812e24b0)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e3702)
Location: include/linux/uaccess.h:97
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81340666)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81343d3f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff81764146)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff81031209)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f42f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ff6e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040a1f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041fa6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043574)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109193b)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812f3f69)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f73b4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81358bb6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c132)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff81788136)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/fpu/regset.c (ffffffff810425df)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104279a)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043c70)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044b37)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81046dfd)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In fs/select.c (ffffffff8132ffdb)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff810431c8)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff8133b930)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff81044ad8)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff81341e2c)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff8104ad72)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff8138f7ec)
Location: include/linux/uaccess.h:141
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff810551a0)
Location: include/linux/uaccess.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff814107f1)
Location: include/linux/uaccess.h:101
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff81062de0)
Location: include/linux/uaccess.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff8149b4c1)
Location: include/linux/uaccess.h:109
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff81063ba1)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff814d0775)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/x86/kernel/fpu/signal.c (ffffffff8106b0cd)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In fs/select.c (ffffffff815030b1)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In arch/arm64/kernel/ptrace.c (ffff80001008b5e8)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:sve_get
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
```
```
In arch/arm64/kernel/signal.c (ffff800010091124)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
```
```
In virt/kvm/kvm_main.c (ffff8000100b99a0)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
```
```
In fs/readdir.c (ffff80001039f7c8)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffff8000103a46dc)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffff80001041e36c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffff800010421e4c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffff800010994e78)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/arm/kernel/ptrace.c (c030c410)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:fpa_get
  - arch/arm/kernel/ptrace.c:gpr_get
```
```
In arch/arm/kernel/signal.c (c030e484)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:preserve_vfp_context
  - arch/arm/kernel/signal.c:preserve_iwmmxt_context
```
```
In fs/readdir.c (c0584670)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (c05862c8)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (c05e69b4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/binfmt_elf_fdpic.c (c05ea484)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
```
```
In drivers/scsi/sg.c (c0a653a8)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/powerpc/kernel/ptrace.c (c0000000000143f4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_get
  - arch/powerpc/kernel/ptrace.c:ebb_get
  - arch/powerpc/kernel/ptrace.c:tar_get
  - arch/powerpc/kernel/ptrace.c:dscr_get
  - arch/powerpc/kernel/ptrace.c:ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_dscr_get
  - arch/powerpc/kernel/ptrace.c:tm_ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_tar_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:vsr_get
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:fpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001ca48)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_to_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_to_user
```
```
In arch/powerpc/kernel/signal_64.c (c000000000034540)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
```
In fs/readdir.c (c00000000049af4c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (c00000000049e36c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (c00000000052cf9c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (c000000000530c8c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (c000000000a56c48)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b60fc)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_fpr_get
  - arch/riscv/kernel/ptrace.c:riscv_fpr_get
  - arch/riscv/kernel/ptrace.c:riscv_gpr_get
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b669c)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
```
```
In fs/readdir.c (ffffffe00026a3ba)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffe00026b6b4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffe0002c091e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffe0005f65a0)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff81031369)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f5af)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810400ee)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040b9f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042126)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff810436f4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810908fb)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812ec549)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef994)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81351196)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81354712)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff8173c826)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff81020d76)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102edaf)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f8ee)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103037f)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff810317e6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81032d14)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f40b)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812dd179)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e05c4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81341e76)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813453d2)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff8171e4c6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff810311c9)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f3ef)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ff2e)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810409df)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041f66)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043534)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810908ab)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812ea359)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ed7a4)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff8134ec66)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813521e2)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff8177cfb6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
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
In arch/x86/kernel/signal.c (ffffffff81032076)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810406cf)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810412ce)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041dbf)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81043346)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81044934)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092c8b)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In fs/readdir.c (ffffffff812fb349)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fe7ae)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff813621e6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813659a2)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In drivers/scsi/sg.c (ffffffff81796de6)
Location: include/linux/uaccess.h:97
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl
```
</details>
</li>
</ul>

## Differences
