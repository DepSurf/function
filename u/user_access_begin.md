# Function: <code>user_access_begin</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b22c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff811467cc)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In lib/strncpy_from_user.c (ffffffff8150ac36)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150adbe)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In kernel/exit.c (ffffffff8109f88c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff81151905)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In lib/strncpy_from_user.c (ffffffff815393a7)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815394e9)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In kernel/exit.c (ffffffff810a5f0c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff8115d555)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff812f42e3)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In lib/usercopy.c (ffffffff8152c1b6)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8155a1bc)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a2ef)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In arch/x86/kernel/signal.c (ffffffff81033336)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a382)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096f90)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810adab1)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff8115a986)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116df95)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff8132c65e)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8132eab2)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/usercopy.c (ffffffff8158fa86)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815e3aec)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3c12)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd2d6)
Location: arch/x86/include/asm/uaccess.h:481
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/signal.c (ffffffff81033d86)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ab82)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810961f0)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810a912f)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff811569b6)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116a595)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff81337c69)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8133a9f2)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In lib/iov_iter.c (ffffffff815a40e9)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In lib/usercopy.c (ffffffff815ac5b0)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81607fac)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816080e4)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621fcd)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/signal.c (ffffffff81035882)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c582)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096ae0)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810aa1ac)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff81157dd6)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116b208)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff8125addb)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8133e3dc)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff813408b1)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff815ab05a)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
```
```
In lib/usercopy.c (ffffffff815b7286)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815eac74)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815ead99)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058dd)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In net/core/scm.c (ffffffff819dc570)
Location: arch/x86/include/asm/uaccess.h:474
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal.c (ffffffff8103ab62)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81042082)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6a80)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810bbcec)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff8117cc56)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81190e08)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81296bd0)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8138bd6c)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8138e281)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff8161496a)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
```
```
In lib/usercopy.c (ffffffff8161d8b6)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81657174)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81657299)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741cd)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In net/core/scm.c (ffffffff81a8c7b0)
Location: arch/x86/include/asm/uaccess.h:475
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal.c (ffffffff81041dc4)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049d72)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbd50)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810d27d8)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff811b2ceb)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811b6744)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff811c05ef)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff812eca4c)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/gup.c (ffffffff81336d49)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff8140d2e6)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8140f56e)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff816e16f2)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
```
```
In lib/usercopy.c (ffffffff816eb412)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8176e9b4)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176eaf9)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e8ee)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In net/core/scm.c (ffffffff81c0203f)
Location: arch/x86/include/asm/uaccess.h:540
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal_64.c (ffffffff8104bc48)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f52)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055d36)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810f1298)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff811f3bbb)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811f7894)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff812029df)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81356fc0)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/gup.c (ffffffff813ae1d9)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff81497d9d)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8149a16e)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff817d1ce2)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
```
```
In lib/usercopy.c (ffffffff817dbae2)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8189e2c4)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e419)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In net/core/scm.c (ffffffff81db165e)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c21e)
Location: arch/x86/include/asm/uaccess.h:549
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/signal_64.c (ffffffff8104c4d4)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81056180)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056d23)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810fd208)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff8120835b)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8120c2e4)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff81217d98)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81388117)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/gup.c (ffffffff813e250e)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff814ccd10)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff814cf23d)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff818109f0)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In lib/usercopy.c (ffffffff8181ae96)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff818e0890)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e09f5)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In net/core/scm.c (ffffffff81e21baa)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab1c)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/signal_64.c (ffffffff81053754)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d3d0)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105df73)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff81107748)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff8121f1eb)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff812235e4)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff8122f958)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff813b1b77)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/gup.c (ffffffff8140cd3e)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff814ff300)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81501b7d)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In io_uring/waitid.c (ffffffff8182a620)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_copy_si
  - io_uring/waitid.c:io_waitid_copy_si
```
```
In lib/iov_iter.c (ffffffff81856d70)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In lib/usercopy.c (ffffffff818601e6)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff819273d0)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81927538)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In net/core/scm.c (ffffffff81edfaca)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a535c)
Location: arch/x86/include/asm/uaccess.h:519
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In kernel/exit.c (ffffffff8109f82c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff81155b75)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff812ec8c3)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In lib/usercopy.c (ffffffff81524796)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8155279c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815528cf)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In kernel/exit.c (ffffffff8108e25c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff81148e95)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff812dd4f3)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In lib/usercopy.c (ffffffff81514a76)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81542a7c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542baf)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In kernel/exit.c (ffffffff8109f7dc)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff81153945)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff812ea6d3)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In lib/usercopy.c (ffffffff81520826)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8154e4dc)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e60f)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In kernel/exit.c (ffffffff810a773c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/compat.c (ffffffff81160845)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff812fb6c3)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
```
```
In lib/usercopy.c (ffffffff8153a1a6)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8156832c)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156845f)
Location: arch/x86/include/asm/uaccess.h:712
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
</details>
</li>
</ul>

## Differences
