# Function: <code>master_key_spec_type</code>

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
In fs/crypto/keyring.c (ffffffff8134d455)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffff8134e107)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffff81393209)
Location: fs/crypto/fscrypt_private.h:421
Inline: True
Inline callers:
  - fs/crypto/keyring.c:check_for_busy_inodes
```
```
In fs/crypto/keysetup.c (ffffffff81393fcd)
Location: fs/crypto/fscrypt_private.h:421
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
In fs/crypto/keyring.c (0)
Location: fs/crypto/fscrypt_private.h:512
Inline: True
```
```
In fs/crypto/keysetup.c (ffffffff81beafb5)
Location: fs/crypto/fscrypt_private.h:512
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
In fs/crypto/keyring.c (ffffffff81bdcf19)
Location: fs/crypto/fscrypt_private.h:512
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (ffffffff81bdd00e)
Location: fs/crypto/fscrypt_private.h:512
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
In fs/crypto/keyring.c (ffffffff81cc64e8)
Location: fs/crypto/fscrypt_private.h:512
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (ffffffff81cc66d3)
Location: fs/crypto/fscrypt_private.h:512
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
In fs/crypto/keyring.c (ffffffff81e78957)
Location: fs/crypto/fscrypt_private.h:521
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (ffffffff81e78b31)
Location: fs/crypto/fscrypt_private.h:521
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
In fs/crypto/keyring.c (ffffffff814fe1d7)
Location: fs/crypto/fscrypt_private.h:541
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/fscrypt_private.h:541
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
In fs/crypto/keyring.c (ffffffff815357bd)
Location: fs/crypto/fscrypt_private.h:541
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/fscrypt_private.h:541
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
In fs/crypto/keyring.c (ffffffff8156a78d)
Location: fs/crypto/fscrypt_private.h:593
Inline: True
Inline callers:
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
```
```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/fscrypt_private.h:593
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
In fs/crypto/keyring.c (ffff80001040df1c)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffff80001040f2fc)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (c05dacd4)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (c05dbe50)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (c00000000051b4c4)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (c00000000051cb54)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffe0002b7240)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffe0002b7fb8)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffff81345a35)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffff813466e7)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffff81336715)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffff813373c7)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffff81343505)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffff813441b7)
Location: fs/crypto/fscrypt_private.h:407
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
In fs/crypto/keyring.c (ffffffff813567e5)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/keysetup.c (ffffffff81357495)
Location: fs/crypto/fscrypt_private.h:407
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
</ul>

## Differences
