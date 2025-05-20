# Function: <code>__copy_from_user</code>

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
In arch/x86/kernel/signal.c (ffffffff8102ed0f)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81031796)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a5c2)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ad10)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff8103db16)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810782c5)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
```
In fs/compat_ioctl.c (ffffffff812666b1)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In block/compat_ioctl.c (ffffffff813e592c)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff813fb981)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff815c39c8)
Location: arch/x86/include/asm/uaccess_64.h:95
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/kernel/signal.c (ffffffff8102de28)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff810308a9)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a410)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a56b)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b6cb)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103d946)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079866)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In block/compat_ioctl.c (ffffffff8142bc1b)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In lib/iov_iter.c (ffffffff81444deb)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8161f33a)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
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
In arch/x86/kernel/signal.c (ffffffff8102dc88)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030509)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039d00)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039e5a)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103af6b)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103d236)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d656)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In fs/pstore/platform.c (ffffffff8136ba73)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_write_buf_user_compat
```
```
In block/compat_ioctl.c (ffffffff81445a1b)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b7f6)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:_copy_from_user
```
```
In lib/iov_iter.c (ffffffff81462b25)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
```
```
In drivers/scsi/sg.c (ffffffff8164fea8)
Location: arch/x86/include/asm/uaccess_64.h:111
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
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
In arch/x86/kernel/signal.c (ffffffff8102bf08)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81037c15)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037d75)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038e22)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/tls.c (ffffffff8103b293)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107be46)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff81664728)
Location: include/linux/uaccess.h:69
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/kernel/signal.c (ffffffff8102cc25)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81039ec5)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a025)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b35e)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff8103dcc3)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81082542)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff816cdd78)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
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
In arch/x86/kernel/signal.c (ffffffff8102de55)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103abc2)
Location: include/linux/uaccess.h:70
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b537)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c88c)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff8103f265)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085c02)
Location: include/linux/uaccess.h:70
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff8170781c)
Location: include/linux/uaccess.h:70
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
In arch/x86/kernel/signal.c (ffffffff8102f095)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c0c2)
Location: include/linux/uaccess.h:67
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ca5c)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ddac)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81040865)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c972)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff8172a376)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff81030e64)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ee73)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f0ab)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810405c2)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81042f14)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090842)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff81765a12)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff81031724)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f583)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f714)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d92)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81043674)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091482)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff81789a02)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042733)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a44)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043fd3)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81046ef6)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
In arch/x86/kernel/fpu/regset.c (ffffffff81042703)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104298b)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043e69)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81046746)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
In arch/x86/kernel/fpu/regset.c (ffffffff810440e3)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104436c)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045b69)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81048164)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a807)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff8104ea74)
Location: include/linux/uaccess.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054cae)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff81059c67)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
Location: include/linux/uaccess.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106280e)
Location: include/linux/uaccess.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
```
In arch/x86/kernel/tls.c (ffffffff81067617)
Location: include/linux/uaccess.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
In arch/x86/kernel/fpu/regset.c (ffffffff810632e2)
Location: include/linux/uaccess.h:93
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106436c)
Location: include/linux/uaccess.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff81068ea8)
Location: include/linux/uaccess.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
In arch/x86/kernel/fpu/regset.c (ffffffff8106a5e3)
Location: include/linux/uaccess.h:93
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b842)
Location: include/linux/uaccess.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff8107031e)
Location: include/linux/uaccess.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
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
In arch/arm64/kernel/ptrace.c (ffff80001008bc70)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
```
```
In arch/arm64/kernel/signal.c (ffff800010092ad8)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
```
```
In virt/kvm/kvm_main.c (ffff8000100bdac4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
```
```
In lib/checksum.c (ffff800010662328)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In drivers/scsi/sg.c (ffff800010991c64)
Location: include/linux/uaccess.h:67
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
In arch/arm/kernel/ptrace.c (c030c5e8)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:fpa_set
  - arch/arm/kernel/ptrace.c:gpr_set
```
```
In arch/arm/kernel/signal.c (c030e1c4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_vfp_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
```
```
In fs/pstore/ram_core.c (c06d74cc)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_update_user
```
```
In drivers/scsi/sg.c (c0a642a0)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
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
In arch/powerpc/kernel/ptrace.c (c0000000000160ac)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001d020)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
```
```
In arch/powerpc/kernel/signal_64.c (c000000000033fb8)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fdac)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
```
```
In arch/powerpc/lib/pmem.c (c0000000000a7f6c)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
```
```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000aa090)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
```
```
In drivers/scsi/sg.c (c000000000a533f8)
Location: include/linux/uaccess.h:67
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b622c)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_fpr_set
  - arch/riscv/kernel/ptrace.c:riscv_gpr_set
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b68c4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
```
In lib/checksum.c (ffffffe00048ebe6)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In drivers/scsi/sg.c (ffffffe0005f4992)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff81031884)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f703)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f894)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040f12)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff810437f4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090442)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff8173e0f2)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff81021264)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ef03)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f094)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810306f2)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81032e14)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ef52)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff8171fd92)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff810316e4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f543)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f6d4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d52)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81043634)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810903f2)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff8177e882)
Location: include/linux/uaccess.h:67
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
In arch/x86/kernel/signal.c (ffffffff81032594)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81040823)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810409c4)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81042132)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/tls.c (ffffffff81044a34)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810927d2)
Location: include/linux/uaccess.h:67
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In drivers/scsi/sg.c (ffffffff81798688)
Location: include/linux/uaccess.h:67
Inline: True
```
</details>
</li>
</ul>

## Differences
