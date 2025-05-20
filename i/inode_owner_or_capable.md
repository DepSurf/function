# Function: <code>inode_owner_or_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812279e0)
Location: fs/inode.c:1956
Inline: True
Direct callers:
  - fs/namei.c:may_linkat
  - fs/namei.c:may_open
  - fs/fcntl.c:SyS_fcntl
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/xattr.c:xattr_permission
  - fs/utimes.c:utimes_common
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812279e0-ffffffff81227a41: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250000)
Location: fs/inode.c:1973
Inline: True
Direct callers:
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/xattr.c:xattr_permission
  - fs/utimes.c:utimes_common
  - fs/crypto/policy.c:fscrypt_process_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81250000-ffffffff81250068: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812630a0)
Location: fs/inode.c:2023
Inline: True
Direct callers:
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812630a0-ffffffff81263108: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270910)
Location: fs/inode.c:2013
Inline: True
Direct callers:
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81270910-ffffffff81270961: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293250)
Location: fs/inode.c:2026
Inline: True
Direct callers:
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81293250-ffffffff8129329f: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8ec0)
Location: fs/inode.c:2024
Inline: True
Direct callers:
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812b8ec0-ffffffff812b8f12: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce000)
Location: fs/inode.c:2031
Inline: True
Direct callers:
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812ce000-ffffffff812ce052: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eae60)
Location: fs/inode.c:2069
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812eae60-ffffffff812eaeb8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc9a0)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812fc9a0-ffffffff812fc9f8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813351d0)
Location: fs/inode.c:2164
Inline: True
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:may_open
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813351d0-ffffffff8133522c: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340b40)
Location: fs/inode.c:2165
Inline: True
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:may_open
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81340b40-ffffffff81340b9c: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346e40)
Location: fs/inode.c:2188
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81346e40-ffffffff81346ea2: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813948a0)
Location: fs/inode.c:2193
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813948a0-ffffffff81394902: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416ed0)
Location: fs/inode.c:2274
Inline: False
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:may_setattr
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81416ed0-ffffffff81416f77: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a24b0)
Location: fs/inode.c:2323
Inline: False
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:may_setattr
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814a24b0-ffffffff814a256d: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d7050)
Location: fs/inode.c:2368
Inline: False
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:may_setattr
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814d7050-ffffffff814d70dc: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inode_owner_or_capable(struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff815093d0)
Location: fs/inode.c:2371
Inline: False
Direct callers:
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - fs/namei.c:may_open
  - fs/namei.c:may_linkat
  - fs/fcntl.c:setfl
  - fs/ioctl.c:vfs_fileattr_set
  - fs/attr.c:may_setattr
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/posix_acl.c:set_posix_acl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff815093d0-ffffffff8150945c: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac390)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffff8000103ac390-ffff8000103ac41c: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d3b4)
Location: fs/inode.c:2080
Inline: False
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:__se_sys_madvise
  - fs/namei.c:do_linkat
  - fs/namei.c:may_open
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c058d3b4-c058d420: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7b00)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c0000000004a7b00-c0000000004a7bac: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002719c0)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffe0002719c0-ffffffe000271a20: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4f80)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812f4f80-ffffffff812f4fd8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5ba0)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812e5ba0-ffffffff812e5bf8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2d90)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff812f2d90-ffffffff812f2de8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool inode_owner_or_capable(const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813044a0)
Location: fs/inode.c:2080
Inline: True
Direct callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - fs/namei.c:do_linkat
  - fs/fcntl.c:setfl
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813044a0-ffffffff813044f8: inode_owner_or_capable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode</code> ➡️ <code>mnt_userns, inode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
