# Function: <code>__copy_to_user_nocheck</code>

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
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a50c)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ac0f)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c715)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d9f2)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810784c1)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81091084)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff810937d0)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In mm/maccess.c (ffffffff811915c6)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff81220722)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81220c89)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff8126401d)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/compat_ioctl.c (ffffffff812661cd)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81321c4a)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81322174)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff813e5c43)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff813fbee1)
Location: arch/x86/include/asm/uaccess_64.h:102
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff815c2704)
Location: arch/x86/include/asm/uaccess_64.h:102
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
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a296)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103abe5)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b563)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c471)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d82d)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079c52)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff81094163)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff810969fd)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In mm/maccess.c (ffffffff811a5dc0)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812481d2)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812488f8)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812901be)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/binfmt_elf.c (ffffffff81356fd8)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813574ef)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff8142c04a)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff8144498a)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8161b14d)
Location: arch/x86/include/asm/uaccess_64.h:119
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
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039b86)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a485)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ae03)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bd01)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103d11d)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107da22)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff81099142)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109b9ad)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In mm/maccess.c (ffffffff811b6140)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff8125b202)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8125b928)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/compat.c (ffffffff812a51fe)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/compat.c:compat_fillonedir
```
```
In fs/binfmt_elf.c (ffffffff8136d44f)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8136d9df)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In block/compat_ioctl.c (ffffffff81445e4a)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b706)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:_copy_to_user
```
```
In lib/iov_iter.c (ffffffff81463145)
Location: arch/x86/include/asm/uaccess_64.h:119
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8164bdc6)
Location: arch/x86/include/asm/uaccess_64.h:119
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
