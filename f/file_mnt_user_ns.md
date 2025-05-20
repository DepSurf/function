# Function: <code>file_mnt_user_ns</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be5b7)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff812a6816)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff812c7c90)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff8130b014)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81320682)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff8132cf4d)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/fcntl.c (ffffffff8133b5a1)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff8133d90f)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8134744b)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/xattr.c (ffffffff81356aa5)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/remap_range.c (ffffffff8136caca)
Location: include/linux/fs.h:2759
Inline: True
```
```
In fs/verity/enable.c (ffffffff813af3ee)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff813c0477)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff8141a7c5)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff8147a40b)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff814ca551)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff8151b2c5)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81526ce6)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff81529d42)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8153bde8)
Location: include/linux/fs.h:2759
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
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
In kernel/sys.c (ffffffff810d0323)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff812e7cec)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff8130ca50)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff81355894)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136d1b2)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff8137a64d)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/fcntl.c (ffffffff81389207)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff8138b28f)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff81394eab)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/xattr.c (ffffffff813a5485)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/remap_range.c (ffffffff813bb78a)
Location: include/linux/fs.h:2732
Inline: True
```
```
In fs/verity/enable.c (ffffffff813fef9e)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff8141029f)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff8146d9a5)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff814d1a6b)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff81522ffd)
Location: include/linux/fs.h:2732
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81579345)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81584f76)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff815880e2)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8159aa48)
Location: include/linux/fs.h:2732
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
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
In kernel/sys.c (ffffffff810e9265)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff81348f5e)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff81375679)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff813ce251)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ebde0)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff813f9d8c)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:would_dump
```
```
In fs/fcntl.c (ffffffff8140a86e)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8140c57e)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8141726a)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/xattr.c (ffffffff81428ae3)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/remap_range.c (ffffffff81441992)
Location: include/linux/fs.h:2593
Inline: True
```
```
In fs/verity/enable.c (ffffffff81472b30)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff81485caf)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff814ee256)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff8155e6f1)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff815b6fed)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff81617435)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81624b16)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff816287b4)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8163f800)
Location: include/linux/fs.h:2593
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
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
In kernel/sys.c (ffffffff8110a115)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff813c1305)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff813f3597)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff8145377f)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81474286)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff81483677)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:would_dump
```
```
In fs/fcntl.c (ffffffff81494924)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff81496fb5)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff814a2b58)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
```
```
In fs/remap_range.c (ffffffff814d0c42)
Location: include/linux/fs.h:2728
Inline: True
```
```
In fs/verity/enable.c (ffffffff81504880)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff8151946b)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff8158814b)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff816008b6)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff81661f83)
Location: include/linux/fs.h:2728
Inline: True
```
```
In security/apparmor/domain.c (ffffffff816ca2a9)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff816d88fb)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff816dcf57)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff816f75a2)
Location: include/linux/fs.h:2728
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
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
