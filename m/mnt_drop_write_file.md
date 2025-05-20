# Function: <code>mnt_drop_write_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b870)
Location: fs/namespace.c:488
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fremovexattr
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff8122b870-ffffffff8122b895: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81253fe0)
Location: fs/namespace.c:488
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_fsetxattr
  - fs/crypto/policy.c:fscrypt_process_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81253fe0-ffffffff81254005: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267320)
Location: fs/namespace.c:487
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81267320-ffffffff81267345: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274b80)
Location: fs/namespace.c:488
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81274b80-ffffffff81274ba5: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812974b0)
Location: fs/namespace.c:547
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812974b0-ffffffff812974d9: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd6a0)
Location: fs/namespace.c:548
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812bd6a0-ffffffff812bd6c9: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2990)
Location: fs/namespace.c:459
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_generic_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812d2990-ffffffff812d29b9: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efb60)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812efb60-ffffffff812efb89: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301630)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81301630-ffffffff81301659: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a710)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
```
**Symbols:**

```
ffffffff8133a710-ffffffff8133a739: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346a60)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
```
**Symbols:**

```
ffffffff81346a60-ffffffff81346ab0: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cd40)
Location: fs/namespace.c:463
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8134cd40-ffffffff8134cd96: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139acb0)
Location: fs/namespace.c:465
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8139acb0-ffffffff8139ad06: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e6e0)
Location: fs/namespace.c:481
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8141e6e0-ffffffff8141e775: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aadf0)
Location: fs/namespace.c:596
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff814aadf0-ffffffff814aae85: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfca0)
Location: fs/namespace.c:491
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setlabel
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff814dfca0-ffffffff814dfd3b: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81512ba0)
Location: fs/namespace.c:498
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/ioctl.c:do_vfs_ioctl
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setlabel
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff81512ba0-ffffffff81512c3b: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4a60)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffff8000103b4a60-ffff8000103b4abc: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592c08)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
c0592c08-c0592c58: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0e80)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
c0000000004b0e80-c0000000004b0efc: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277570)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffe000277570-ffffffe0002775ca: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9c10)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812f9c10-ffffffff812f9c39: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea830)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812ea830-ffffffff812ea859: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7a00)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812f7a00-ffffffff812f7a29: mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308d30)
Location: fs/namespace.c:456
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81308d30-ffffffff81308d70: mnt_drop_write_file (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
