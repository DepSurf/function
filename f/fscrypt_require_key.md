# Function: <code>fscrypt_require_key</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812d0bdc)
Location: include/linux/fscrypt.h:168
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff8132ba57)
Location: include/linux/fscrypt.h:168
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff812fb2d7)
Location: include/linux/fscrypt.h:64
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff8135a1b1)
Location: include/linux/fscrypt.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff813106e7)
Location: include/linux/fscrypt.h:64
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff813724eb)
Location: include/linux/fscrypt.h:64
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff81337c8f)
Location: include/linux/fscrypt.h:525
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff8139bafe)
Location: include/linux/fscrypt.h:525
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff8134bd0f)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff813b438e)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff8139187f)
Location: include/linux/fscrypt.h:553
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/ext4/inode.c (ffffffff813ff7c1)
Location: include/linux/fscrypt.h:553
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff813a2e5a)
Location: fs/crypto/fscrypt_private.h:588
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff813a6a6e)
Location: fs/crypto/fscrypt_private.h:588
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/hooks.c (ffffffff813aa09a)
Location: fs/crypto/fscrypt_private.h:588
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff813adafe)
Location: fs/crypto/fscrypt_private.h:588
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/hooks.c (ffffffff813f98ea)
Location: fs/crypto/fscrypt_private.h:589
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff813fd47e)
Location: fs/crypto/fscrypt_private.h:589
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/hooks.c (ffffffff8146c7d4)
Location: fs/crypto/fscrypt_private.h:600
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff81470c66)
Location: fs/crypto/fscrypt_private.h:600
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
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
In fs/crypto/hooks.c (ffffffff814fdbe4)
Location: fs/crypto/fscrypt_private.h:626
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff81502746)
Location: fs/crypto/fscrypt_private.h:626
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff8150335a)
Location: fs/crypto/fscrypt_private.h:626
Inline: True
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
In fs/crypto/hooks.c (ffffffff815351d4)
Location: fs/crypto/fscrypt_private.h:629
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff81539de6)
Location: fs/crypto/fscrypt_private.h:629
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff8153ac0a)
Location: fs/crypto/fscrypt_private.h:629
Inline: True
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
In fs/crypto/hooks.c (ffffffff8156a194)
Location: fs/crypto/fscrypt_private.h:682
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/policy.c (ffffffff8156efe6)
Location: fs/crypto/fscrypt_private.h:682
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_policy_to_inherit
```
```
In fs/crypto/inline_crypt.c (ffffffff8156fe8a)
Location: fs/crypto/fscrypt_private.h:682
Inline: True
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
In fs/crypto/hooks.c (ffff80001040c5ac)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffff800010488b58)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (c05d96a0)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (c064af68)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (c00000000051982c)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (c0000000005af718)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffe0002b5fb2)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffe0003104fa)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff813442ef)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff813ac96e)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff81334fcf)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff8139d3fe)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff81341dbf)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff813aa1ce)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/crypto/hooks.c (ffffffff813550bf)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:__fscrypt_prepare_link
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/ext4/inode.c (ffffffff813beade)
Location: include/linux/fscrypt.h:574
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
</details>
</li>
</ul>

## Differences
