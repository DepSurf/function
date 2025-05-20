# Function: <code>retry_estale</code>

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
In fs/open.c (ffffffff81209a5b)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/open.c:do_sys_truncate
  - fs/open.c:SyS_access
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
```
```
In fs/stat.c (ffffffff81211603)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff8121c87c)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_unlinkat
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
```
```
In fs/xattr.c (ffffffff812322df)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81240f40)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81241b63)
Location: include/linux/namei.h:106
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff81230f83)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff81238970)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
```
```
In fs/namei.c (ffffffff8124607b)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
```
In fs/xattr.c (ffffffff8125aff7)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81269271)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81269eb3)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff81243533)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff8124b644)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
```
```
In fs/namei.c (ffffffff81258ffc)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
```
In fs/xattr.c (ffffffff8126e597)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8127c221)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8127ce63)
Location: include/linux/namei.h:110
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff8124ec86)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
```
```
In fs/stat.c (ffffffff81257776)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81264fb6)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
```
In fs/xattr.c (ffffffff8127bd97)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81289540)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8128a745)
Location: include/linux/namei.h:111
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff81270c06)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
```
```
In fs/stat.c (ffffffff812799c6)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81287846)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
```
In fs/xattr.c (ffffffff8129e837)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812ac060)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ad465)
Location: include/linux/namei.h:112
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff81296788)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812a045b)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812ac92c)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff812c52e7)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812d2d13)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812d50a5)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812ab578)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812b543b)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812c1a2c)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff812da4e7)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812e80f3)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ea475)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812c7d78)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812d21eb)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812ddf80)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff812f8ac1)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813069f7)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81308ed7)
Location: include/linux/namei.h:116
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812d9788)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812e3d7b)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812efaa0)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff8130a6f1)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81319a57)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131bf47)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff8130f548)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8131a65b)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81327d58)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff813436f1)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813539f9)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81355c57)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff8131b778)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff81325ceb)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff8133484d)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff8134f881)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813602f9)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81362597)
Location: include/linux/namei.h:99
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff813218c8)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8132be1b)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff8133a91d)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff813563a1)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81366d99)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81369037)
Location: include/linux/namei.h:100
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff8136eda8)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8137958b)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81388576)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
```
```
In fs/xattr.c (ffffffff813a48d1)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813b58e9)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813b7d37)
Location: include/linux/namei.h:98
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff813ed688)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff813f8a55)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff814095a4)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
```
```
In fs/xattr.c (ffffffff81428921)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8143ac54)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8143d505)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In io_uring/io_uring.c (ffffffff816d271f)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_getxattr
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
In fs/open.c (ffffffff81475d28)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff81481fd5)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81493c54)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
```
```
In fs/xattr.c (ffffffff814b5f31)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff814c9114)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff814cbd45)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In io_uring/xattr.c (ffffffff81792f5f)
Location: include/linux/namei.h:104
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
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
In fs/open.c (ffffffff814aa648)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff814b6be5)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff814c8cb6)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
```
```
In fs/xattr.c (ffffffff814ea761)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff814ff357)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81501f85)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In io_uring/xattr.c (ffffffff817d3cbf)
Location: include/linux/namei.h:113
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
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
In fs/open.c (ffffffff814dbacd)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:__x64_sys_truncate
```
```
In fs/stat.c (ffffffff814e8f15)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff814fb566)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
```
```
In fs/xattr.c (ffffffff8151e601)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81533f60)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81536bd5)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In io_uring/xattr.c (ffffffff81817b4c)
Location: include/linux/namei.h:138
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
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
In fs/open.c (ffff80001037eb0c)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffff80001038a818)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffff8000103991d8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffff8000103be160)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffff8000103d0a34)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffff8000103d38e8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (c0569474)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (c0572da0)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (c057f874)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (c059b998)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (c05abd80)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c05ade54)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (c0000000004747a8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (c000000000482bc8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (c000000000493930)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (c0000000004bcc74)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (c0000000004d33b8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c0000000004d62f4)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffe000254714)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffe00025cae2)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffe000266ca6)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffe00027f508)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffe00028cbb0)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffe00028e290)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812d1d68)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812dc35b)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812e8080)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff81302cd1)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81312037)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81314527)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812c29e8)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812ccfdb)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812d8cc0)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff812f38f1)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81302c47)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81305137)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812cfb78)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812da16b)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812e5e90)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff81300ac1)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8130fe27)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81312317)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
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
In fs/open.c (ffffffff812e0988)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812eb07b)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812f6e10)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
```
```
In fs/xattr.c (ffffffff81311e01)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81321627)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81323b57)
Location: include/linux/namei.h:89
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
</details>
</li>
</ul>

## Differences
