# Function: <code>fscrypt_get_info</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a2281)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813a2b74)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813a4575)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813a6a7d)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/inode.c (ffffffff81410002)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/fname.c (ffffffff813a9401)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813a9d08)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813ab765)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813adb0d)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/hash.c (ffffffff81404552)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff814163c0)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8142bcee)
Location: include/linux/fscrypt.h:75
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/fname.c (ffffffff813f8b71)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813f9548)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813faff5)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813fd48d)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/hash.c (ffffffff81456d02)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff81469945)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8147fb8e)
Location: include/linux/fscrypt.h:176
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/fname.c (ffffffff8146b921)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff8146c467)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff8146e2f5)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81470c75)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_get_policy
```
```
In fs/ext4/hash.c (ffffffff814d4795)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff814e9757)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff81500015)
Location: include/linux/fscrypt.h:184
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/fname.c (ffffffff814fcc01)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff814fd807)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff814ff945)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81502755)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_get_policy
```
```
In fs/crypto/inline_crypt.c (ffffffff81503375)
Location: include/linux/fscrypt.h:181
Inline: True
```
```
In fs/ext4/hash.c (ffffffff8156d455)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff81583260)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8159a805)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/fname.c (ffffffff81534181)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81534d67)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff81536f15)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81539df5)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_get_policy
```
```
In fs/crypto/inline_crypt.c (ffffffff8153ac25)
Location: include/linux/fscrypt.h:181
Inline: True
```
```
In fs/ext4/hash.c (ffffffff815a5345)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff815b9e20)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff815d10a5)
Location: include/linux/fscrypt.h:181
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
</details>
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
