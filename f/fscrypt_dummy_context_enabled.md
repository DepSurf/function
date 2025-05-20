# Function: <code>fscrypt_dummy_context_enabled</code>

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
In fs/crypto/policy.c (ffffffff81289ea4)
Location: include/linux/fscrypto.h:187
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_inherit_context
```
```
In fs/crypto/keyinfo.c (ffffffff8128a5cb)
Location: include/linux/fscrypto.h:187
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
In fs/crypto/policy.c (ffffffff8129ebc4)
Location: include/linux/fscrypto.h:99
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_inherit_context
```
```
In fs/crypto/keyinfo.c (ffffffff8129f2da)
Location: include/linux/fscrypto.h:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812addb6)
Location: include/linux/fscrypt_common.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812d1200)
Location: include/linux/fscrypt.h:92
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
In fs/crypto/keyinfo.c (ffffffff812fbbf8)
Location: include/linux/fscrypt_supp.h:55
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8136f809)
Location: include/linux/fscrypt_supp.h:55
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keyinfo.c (ffffffff81311395)
Location: include/linux/fscrypt_supp.h:55
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81387c99)
Location: include/linux/fscrypt_supp.h:55
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keyinfo.c (ffffffff81338a62)
Location: include/linux/fscrypt.h:84
Inline: True
```
```
In fs/ext4/namei.c (ffffffff813b1cff)
Location: include/linux/fscrypt.h:84
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffff8134db72)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffff813cad4f)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
In fs/crypto/keysetup.c (ffff80001040ee80)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffff8000104a2974)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (c05db99c)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (c0664bcc)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (c00000000051c570)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (c0000000005cf8fc)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffe0002b7c12)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffe000324590)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffff81346152)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffff813c332f)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffff81336e32)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffff813b3dbf)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffff81343c22)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffff813c07bf)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
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
In fs/crypto/keysetup.c (ffffffff81356f02)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ext4/namei.c (ffffffff813d58ef)
Location: include/linux/fscrypt.h:85
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
</ul>

## Differences
