# Function: <code>fscrypt_has_encryption_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (0)
Location: include/linux/fscrypto.h:233
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypto.h:233
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypto.h:233
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/fscrypto.h:233
Inline: True
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
In fs/ext4/file.c (0)
Location: include/linux/fscrypto.h:138
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypto.h:138
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypto.h:138
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/fscrypto.h:138
Inline: True
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
In fs/ext4/file.c (0)
Location: include/linux/fscrypt_common.h:132
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypt_common.h:132
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypt_common.h:132
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/fscrypt_common.h:132
Inline: True
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
In fs/crypto/hooks.c (0)
Location: include/linux/fscrypt.h:132
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypt.h:132
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypt.h:132
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/fscrypt.h:132
Inline: True
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
In fs/crypto/hooks.c (0)
Location: include/linux/fscrypt_supp.h:50
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypt_supp.h:50
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypt_supp.h:50
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
In fs/crypto/hooks.c (0)
Location: include/linux/fscrypt_supp.h:50
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/fscrypt_supp.h:50
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/fscrypt_supp.h:50
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
In fs/crypto/crypto.c (ffffffff81336a2c)
Location: include/linux/fscrypt.h:78
Inline: True
```
```
In fs/crypto/fname.c (ffffffff813377c8)
Location: include/linux/fscrypt.h:78
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81337b79)
Location: include/linux/fscrypt.h:78
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keyinfo.c (ffffffff81338cb5)
Location: include/linux/fscrypt.h:78
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81389153)
Location: include/linux/fscrypt.h:78
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8139bc3a)
Location: include/linux/fscrypt.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffff8134a5ac)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8134b3e9)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff8134bbf6)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffff8134daf7)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff813a1826)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813b43ac)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/fname.c (ffffffff81390dc8)
Location: include/linux/fscrypt.h:74
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81391562)
Location: include/linux/fscrypt.h:74
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff81393a76)
Location: include/linux/fscrypt.h:74
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff813edba6)
Location: include/linux/fscrypt.h:74
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813ff7df)
Location: include/linux/fscrypt.h:74
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/fname.c (ffffffff813a2281)
Location: include/linux/fscrypt.h:681
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813a2b74)
Location: include/linux/fscrypt.h:681
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813a53d3)
Location: include/linux/fscrypt.h:681
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813a6a7d)
Location: include/linux/fscrypt.h:681
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/inode.c (ffffffff81410002)
Location: include/linux/fscrypt.h:681
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
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813a9d08)
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813ac4b3)
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813adb0d)
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/hash.c (ffffffff81404552)
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff814163c0)
Location: include/linux/fscrypt.h:688
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8142bcee)
Location: include/linux/fscrypt.h:688
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
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813f9548)
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff813fbe23)
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff813fd48d)
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/hash.c (ffffffff81456d02)
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff81469945)
Location: include/linux/fscrypt.h:789
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8147fb8e)
Location: include/linux/fscrypt.h:789
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
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff8146c467)
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff8146f22a)
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81470c75)
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/ext4/hash.c (ffffffff814d4795)
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff814e9757)
Location: include/linux/fscrypt.h:853
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff81500015)
Location: include/linux/fscrypt.h:853
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
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff814fd807)
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff8150092a)
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81502755)
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff81503375)
Location: include/linux/fscrypt.h:851
Inline: True
```
```
In fs/ext4/hash.c (ffffffff8156d455)
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff81583260)
Location: include/linux/fscrypt.h:851
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff8159a805)
Location: include/linux/fscrypt.h:851
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
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81534d67)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff81537fba)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff81539df5)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff8153ac25)
Location: include/linux/fscrypt.h:869
Inline: True
```
```
In fs/ext4/hash.c (ffffffff815a5345)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff815b9e20)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff815d10a5)
Location: include/linux/fscrypt.h:869
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/fname.c (ffffffff81569111)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81569d27)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff8156d10a)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff8156eff5)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff8156fea5)
Location: include/linux/fscrypt.h:885
Inline: True
```
```
In fs/ext4/hash.c (ffffffff815de1bb)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff815f2b88)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff816097da)
Location: include/linux/fscrypt.h:885
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
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
In fs/crypto/crypto.c (ffff80001040aa70)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffff80001040be28)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffff80001040c7c8)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffff80001040ee0c)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffff800010474f74)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffff800010488b70)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (c05d7f04)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (c05d8b80)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (c05d993c)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (c05db928)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (c0636680)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c064af84)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (c00000000051769c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (c000000000518bc4)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (c000000000519674)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (c00000000051c4dc)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (c000000000596a40)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c0000000005afaf4)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffe0002b4a6c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffe0002b5532)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffe0002b5ec4)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffe0002b7bca)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffe000300782)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffe000310514)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffff81342b8c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffff813439c9)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff813441d6)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffff813460d7)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff81399e06)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813ac98c)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffff8133386c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffff813346a9)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81334eb6)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffff81336db7)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff8138a896)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8139d41c)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffff8134065c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81341499)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81341ca6)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffff81343ba7)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff81397666)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813aa1ec)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
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
In fs/crypto/crypto.c (ffffffff8135395c)
Location: include/linux/fscrypt.h:79
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81354799)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81354fa6)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/crypto/keysetup.c (ffffffff81356e87)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/ialloc.c (ffffffff813abe92)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813beafc)
Location: include/linux/fscrypt.h:79
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
</details>
</li>
</ul>

## Differences
