# Function: <code>fscrypt_get_inode_info</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
```
In fs/crypto/hooks.c (ffffffff81569d27)
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keysetup.c (ffffffff8156bfc5)
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/crypto/policy.c (ffffffff8156eff5)
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
  - fs/crypto/policy.c:fscrypt_get_policy
```
```
In fs/crypto/inline_crypt.c (ffffffff8156fea5)
Location: include/linux/fscrypt.h:196
Inline: True
```
```
In fs/ext4/hash.c (ffffffff815de1bb)
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:__ext4fs_dirhash
```
```
In fs/ext4/inode.c (ffffffff815f2b88)
Location: include/linux/fscrypt.h:196
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/namei.c (ffffffff816097da)
Location: include/linux/fscrypt.h:196
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
