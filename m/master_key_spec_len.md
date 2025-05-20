# Function: <code>master_key_spec_len</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134d1fa)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffff8134e095)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffff81392ae8)
Location: fs/crypto/fscrypt_private.h:433
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:check_for_busy_inodes
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81393f73)
Location: fs/crypto/fscrypt_private.h:433
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff813a3e58)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:check_for_busy_inodes
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81beaf5e)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff813ab098)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81bdcfb7)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff813fa928)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81cc6678)
Location: fs/crypto/fscrypt_private.h:524
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff8146dc99)
Location: fs/crypto/fscrypt_private.h:533
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81e78ae1)
Location: fs/crypto/fscrypt_private.h:533
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff814ff289)
Location: fs/crypto/fscrypt_private.h:553
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/keysetup.c (ffffffff815006d7)
Location: fs/crypto/fscrypt_private.h:553
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
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
In fs/crypto/keyring.c (ffffffff815367aa)
Location: fs/crypto/fscrypt_private.h:553
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/keysetup.c (ffffffff81537a7d)
Location: fs/crypto/fscrypt_private.h:553
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffffffff8156b81c)
Location: fs/crypto/fscrypt_private.h:605
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/keysetup.c (ffffffff8156cb71)
Location: fs/crypto/fscrypt_private.h:605
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
In fs/crypto/keyring.c (ffff80001040e184)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (c05dae54)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (c05dbec0)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (c00000000051b664)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffe0002b735e)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffe0002b7fc6)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffff813457da)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffff81346675)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffff813364ba)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffff81337355)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffff813432aa)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffff81344145)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
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
In fs/crypto/keyring.c (ffffffff8135658a)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:format_mk_description
```
```
In fs/crypto/keysetup.c (ffffffff81357423)
Location: fs/crypto/fscrypt_private.h:419
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
</ul>

## Differences
