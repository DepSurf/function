# Function: <code>raw_copy_to_user</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102b87d)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81037ac5)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81038325)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038ce4)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff81039d24)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103b191)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c20b)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810963e8)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109879d)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In mm/maccess.c (ffffffff811be09c)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff81267c08)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81268790)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/binfmt_elf.c (ffffffff812b71be)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ba1c8)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff81465014)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8146c645)
Location: arch/x86/include/asm/uaccess_64.h:106
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff816607ea)
Location: arch/x86/include/asm/uaccess_64.h:106
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
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039d75)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a5a7)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103a7bd)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c724)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8103dbc1)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108290b)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff8109d17e)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109f47d)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In mm/maccess.c (ffffffff811d2d5d)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff8128a4b8)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8128b040)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - fs/select.c:set_fd_set
```
```
In fs/binfmt_elf.c (ffffffff812daa63)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ddaab)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff81490f91)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81498961)
Location: arch/x86/include/asm/uaccess_64.h:107
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff816c9d0a)
Location: arch/x86/include/asm/uaccess_64.h:107
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ac7d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b9bf)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103bcbd)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103dc87)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103f168)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085fcb)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff811f40dd)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812b0878)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812b1a6f)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8130363d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81306d2b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff814c61e5)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814cdbb6)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8170668e)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c17d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cecf)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103da3c)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103f257)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104075f)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cd5e)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff8120646d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812c5a32)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812c8fd3)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81318d3a)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c498)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff814da945)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814e2486)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff81728a7e)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ed27)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103eeda)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fa4d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104182b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81042e0f)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090c3b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff8121d75d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812e24c4)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e370f)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81340666)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81343d3f)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff815061e1)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8150e341)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8176415b)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f437)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ff6e)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040a31)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041fab)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043574)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109193b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff8122b1ee)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812f3f7d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f73cb)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81358bb6)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c132)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff81524171)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8152c191)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8178814b)
Location: arch/x86/include/asm/uaccess_64.h:123
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
In arch/x86/kernel/fpu/regset.c (ffffffff810425e7)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104279a)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043c82)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044b3c)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81046dfd)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In mm/maccess.c (ffffffff812580db)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff8132fff2)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff8158b5ea)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/usercopy.c (ffffffff8158fb5d)
Location: arch/x86/include/asm/uaccess_64.h:72
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff812627ed)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff8133b947)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff815a41d8)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff815ac6a8)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff8126724d)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff81341e3c)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff815b14cd)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff815b7347)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff812a3c8d)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff8138f7fc)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff81618fa2)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff8161d977)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff812fbd34)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff81410801)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff816e5c84)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff816eb3ba)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff81365f14)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff8149b4d1)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff817d3c7a)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff817dba7a)
Location: arch/x86/include/asm/uaccess_64.h:56
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff8139837b)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff814d0785)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff818101b9)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8181ae19)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In mm/maccess.c (ffffffff813c219b)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
```
```
In fs/select.c (ffffffff815030c1)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In lib/iov_iter.c (ffffffff818577ef)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff81860189)
Location: arch/x86/include/asm/uaccess_64.h:131
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030cdc4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:fpa_get
  - arch/arm/kernel/ptrace.c:gpr_get
```
```
In arch/arm/kernel/signal.c (c030e484)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:preserve_vfp_context
  - arch/arm/kernel/signal.c:preserve_iwmmxt_context
```
```
In arch/arm/kernel/crash_dump.c (c0315b68)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
```
```
In kernel/exit.c (c035b268)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/exit.c:__se_sys_wait4
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (c035ee24)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/capability.c (c0361184)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capget
```
```
In kernel/ptrace.c (c0363248)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (c036a748)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigprocmask
```
```
In kernel/sys.c (c036ebb0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_getrusage
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__se_sys_times
```
```
In kernel/sched/core.c (c038cd70)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
```
```
In kernel/printk/printk.c (c03c6e64)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/profile.c (c03e3a40)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (c03e4e98)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_timespec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__se_sys_gettimeofday
```
```
In kernel/time/posix-timers.c (c03f7540)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/itimer.c (c03fae5c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_getitimer
```
```
In kernel/seccomp.c (c04493a8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In kernel/relay.c (c044a0e4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (c0464a10)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_read
```
```
In kernel/trace/blktrace.c (c0471ff8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (c0481a6c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/core.c (c049266c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (c0497db8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c049af20)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/btf.c (c04b63e0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
```
```
In kernel/bpf/offload.c (c04ba7a4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (c04bd730)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
```
In kernel/events/core.c (c04cdc34)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
```
In mm/maccess.c (c04e5cd0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In mm/mincore.c (c051c8b8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
```
```
In fs/read_write.c (c056dfec)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_llseek
```
```
In fs/stat.c (c0573348)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
```
```
In fs/pipe.c (c0577f14)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
```
```
In fs/namei.c (c0581284)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (c058255c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c0583ee0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/readdir.c (c0584680)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (c05862d8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (c05923fc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
```
```
In fs/seq_file.c (c059a090)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c059b65c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
```
```
In fs/libfs.c (c059e2b8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
```
```
In fs/splice.c (c05aa270)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/d_path.c (c05ad028)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
```
In fs/statfs.c (c05ada18)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
```
```
In fs/fsopen.c (c05b0794)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (c05c3370)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c50f0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/signalfd.c (c05c8c28)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/userfaultfd.c (c05cd008)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (c05ce8d4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (c05d6ba4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
```
```
In fs/crypto/keyring.c (c05daf80)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (c05dd060)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
```
```
In fs/verity/measure.c (c05deaac)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/binfmt_elf.c (c05e69b4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/binfmt_elf_fdpic.c (c05ea484)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
```
```
In fs/binfmt_flat.c (c05ed250)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/fhandle.c (c05f1fcc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/quota/quota.c (c05febbc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
```
```
In fs/proc/task_mmu.c (c06006fc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
```
```
In fs/proc/base.c (c0604810)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/vmcore.c (c0611ef4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In fs/kernfs/file.c (c06174c8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/dcookies.c (c061fe00)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
```
In fs/ext4/ioctl.c (c064e790)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/fat/dir.c (c06a4970)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (c06a927c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/miscdev.c (c06bb6d4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (c06d85f4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
```
In ipc/msgutil.c (c06da640)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
```
```
In ipc/msg.c (c06dc120)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
```
```
In ipc/sem.c (c06de280)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:copy_semid_to_user
```
```
In ipc/shm.c (c06e0fdc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e5024)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
```
In security/keys/keyctl.c (c06eb200)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
```
```
In security/keys/request_key_auth.c (c06ed87c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (c06ee028)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/dh.c (c06ef56c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/keyctl_pkey.c (c06efc98)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In security/keys/big_key.c (c06f0600)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (c06f2598)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c06f3554)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/selinux/hooks.c (c07011d8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (c07213f4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/tomoyo/common.c (c072cb50)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (c0737e7c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/lsm.c (c074f604)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (c07a4344)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/scsi_ioctl.c (c07b4a10)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b4f9c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/bsg-lib.c (c07b5bfc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/blk-zoned.c (c07c7d58)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c07d89e0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:copyout
```
```
In lib/kfifo.c (c07da864)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
```
```
In drivers/gpio/gpiolib.c (c0861644)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8fb0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (c08cbb44)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
```
```
In drivers/video/fbdev/core/fbcon.c (c08d59b0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (c08dd9c8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
```
```
In drivers/tty/tty_io.c (c095d6b8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/n_tty.c (c0960f14)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (c0963c78)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
```
```
In drivers/tty/vt/vt_ioctl.c (c096be18)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096d644)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/keyboard.c (c0971970)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (c097354c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
```
```
In drivers/tty/vt/vt.c (c097bb00)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
```
```
In drivers/tty/serial/serial_core.c (c09828c0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (c09a747c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09aa4f4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (c09adfa4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In drivers/char/hw_random/core.c (c09b0a44)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b2268)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/lightnvm/core.c (c09d05e8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
```
In drivers/base/regmap/regmap-debugfs.c (c0a00c08)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (c0a07e08)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
```
In drivers/dma-buf/sync_file.c (c0a40ae8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (c0a4160c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c0a45598)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (c0a653a8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
```
```
In drivers/ata/libata-scsi.c (c0a75758)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d400)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/mtd/mtdchar.c (c0a96afc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_writeoob
  - drivers/mtd/mtdchar.c:mtdchar_read
```
```
In drivers/net/tun.c (c0ac7e7c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aceeec)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4208)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c0add108)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/cdrom/cdrom.c (c0ae8110)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
```
In drivers/usb/core/devio.c (c0b067c8)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b082e4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/input/input-compat.c (c0b7b4ac)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
```
```
In drivers/input/mousedev.c (c0b7d40c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (c0b7f850)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
```
```
In drivers/input/misc/uinput.c (c0b84498)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/dev.c (c0b89718)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d45c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_ioctl
```
```
In drivers/i2c/i2c-dev.c (c0b97ab0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In drivers/media/cec/cec-api.c (c0ba4af4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/pps/pps.c (c0ba5984)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c0ba81c0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/watchdog/watchdog_dev.c (c0bc1d74)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
```
In drivers/md/md.c (c0bd4bec)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
```
```
In drivers/md/dm-ioctl.c (c0be7a84)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/mmc/core/block.c (c0c1b3f0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In sound/core/memory.c (c0c84b74)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/memory.c:copy_to_user_fromio
```
```
In sound/core/control.c (c0c877a4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_tlv
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_list
  - sound/core/control.c:snd_ctl_elem_list
```
```
In sound/core/timer.c (c0c8e63c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
```
```
In sound/core/pcm_native.c (c0c95f10)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_info_user
```
```
In sound/core/pcm_lib.c (c0c98184)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:default_read_copy
```
```
In sound/core/compress_offload.c (c0c9e7d4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_get_caps
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbb754)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
```
```
In net/socket.c (c0cc5480)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (c0ccd420)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/scm.c (c0cda444)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (c0cde60c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/sysctl_net_core.c (c0ce0f68)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (c0cf8b14)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
```
```
In net/core/filter.c (c0d1c6c4)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/bpf/test_run.c (c0d62694)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
```
```
In net/ipv4/ip_sockglue.c (c0d76460)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In net/ipv4/tcp.c (c0d82308)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In net/ipv4/raw.c (c0da5328)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In net/ipv4/udp.c (c0da7c64)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
```
```
In net/ipv4/arp.c (c0db0038)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (c0db2c18)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (c0db8d28)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/igmp.c (c0dbe598)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (c0dd9f84)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv6/ipv6_sockglue.c (c0e21f2c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In net/ipv6/raw.c (c0e2d12c)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
```
```
In net/ipv6/mcast.c (c0e34f34)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (c0e42f84)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (c0e49630)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (c0e5d514)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (c0e61054)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (c0e619dc)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:ioctl_private_iw_point
```
```
In net/rfkill/core.c (c0e69ea0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (c0e7a338)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
```
In lib/seq_buf.c (c0e8a8d0)
Location: arch/arm/include/asm/uaccess.h:532
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
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
In arch/powerpc/kernel/ptrace.c (c0000000000143fc)
Location: arch/powerpc/include/asm/uaccess.h:359
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
Location: arch/powerpc/include/asm/uaccess.h:359
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
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
```
In mm/maccess.c (c0000000003717f4)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (c00000000049af54)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (c00000000049e380)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (c00000000052cf9c)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (c000000000530c8c)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (c0000000007d1700)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (c0000000007de1e0)
Location: arch/powerpc/include/asm/uaccess.h:359
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (c000000000a56c48)
Location: arch/powerpc/include/asm/uaccess.h:359
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b610a)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_fpr_get
  - arch/riscv/kernel/ptrace.c:riscv_fpr_get
  - arch/riscv/kernel/ptrace.c:riscv_gpr_get
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b669c)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:handle_signal
```
```
In mm/maccess.c (ffffffe0001dd126)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffe00026a3c8)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffe00026b6c2)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffe0002c091e)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffe00045d686)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffe000464f7c)
Location: arch/riscv/include/asm/uaccess.h:382
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffe0005f65a0)
Location: arch/riscv/include/asm/uaccess.h:382
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f5b7)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810400ee)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040bb1)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104212b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff810436f4)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810908fb)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff8122383e)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812ec55d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef9ab)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81351196)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81354712)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff8151c751)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81524771)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8173c83b)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102edb7)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f8ee)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81030391)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff810317eb)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81032d14)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f40b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff812169ee)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812dd18d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e05db)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff81341e76)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813453d2)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff8150ca41)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81514a51)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8171e4db)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f3f7)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ff2e)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810409f1)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041f6b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81043534)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810908ab)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff812215de)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812ea36d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ed7bb)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff8134ec66)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813521e2)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff815187e1)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81520801)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff8177cfcb)
Location: arch/x86/include/asm/uaccess_64.h:123
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
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810406d7)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810412ce)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041dd1)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104334b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81044934)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092c8b)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In mm/maccess.c (ffffffff8123079e)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
```
In fs/readdir.c (ffffffff812fb35d)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fe7c5)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/binfmt_elf.c (ffffffff813621e6)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813659a2)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/iov_iter.c (ffffffff81532041)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8153a181)
Location: arch/x86/include/asm/uaccess_64.h:123
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
```
```
In drivers/scsi/sg.c (ffffffff81796dfb)
Location: arch/x86/include/asm/uaccess_64.h:123
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
