# Function: <code>file_mnt_idmap</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6143)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
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
In kernel/sys.c (ffffffff811163f1)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff813f6064)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff81426fef)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff81489592)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814a8c39)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff814b8703)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/fcntl.c (ffffffff814c998d)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff814cbded)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff814d7c9f)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
```
```
In fs/xattr.c (ffffffff814ea979)
Location: include/linux/fs.h:2327
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
In fs/remap_range.c (ffffffff81507790)
Location: include/linux/fs.h:2327
Inline: True
```
```
In fs/verity/enable.c (ffffffff8153bfb1)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/locks.c (ffffffff81543e28)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/coredump.c (ffffffff81550d6b)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff815beb50)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff816387af)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff8169a63b)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff81702f5f)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81711747)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8171655a)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff81731826)
Location: include/linux/fs.h:2327
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
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
In kernel/sys.c (ffffffff8111fde1)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff81421d14)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff814602d4)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff814b89f1)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814d9c99)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:do_sys_ftruncate
```
```
In fs/exec.c (ffffffff814eac13)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/fcntl.c (ffffffff814fc23e)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff814fe6a2)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8150a47f)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
```
```
In fs/xattr.c (ffffffff8151e819)
Location: include/linux/fs.h:2557
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
In fs/remap_range.c (ffffffff8153bf28)
Location: include/linux/fs.h:2557
Inline: True
```
```
In fs/verity/enable.c (ffffffff81571291)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/locks.c (ffffffff81579307)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/coredump.c (ffffffff81586bfc)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff815f78fe)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff81671c9f)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In security/commoncap.c (ffffffff816d6d7b)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff8174074f)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8174faae)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/file.c (ffffffff8175502a)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff81772246)
Location: include/linux/fs.h:2557
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
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
