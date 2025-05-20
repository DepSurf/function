# Function: <code>is_master_key_secret_present</code>

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
In fs/crypto/keyring.c (ffffffff8134d27a)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff8134d4a4)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff81391acc)
Location: fs/crypto/fscrypt_private.h:409
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff81392b68)
Location: fs/crypto/fscrypt_private.h:409
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81393264)
Location: fs/crypto/fscrypt_private.h:409
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff813a2ead)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff813a3ed8)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813a45a4)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff813aa0ed)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff813ab118)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813ab794)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff813f993d)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff813fa9a8)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff813fb024)
Location: fs/crypto/fscrypt_private.h:500
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff8146c827)
Location: fs/crypto/fscrypt_private.h:509
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff8146dd18)
Location: fs/crypto/fscrypt_private.h:509
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff8146e324)
Location: fs/crypto/fscrypt_private.h:509
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff814fdc2e)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff814ff2fe)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/crypto/keysetup.c (ffffffff814ff96d)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/hooks.c (ffffffff8153521e)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_prepare_setflags
```
```
In fs/crypto/keyring.c (ffffffff8153681c)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
```
```
In fs/crypto/keysetup.c (ffffffff81536f3d)
Location: fs/crypto/fscrypt_private.h:529
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:setup_file_encryption_key
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040e1ec)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffff80001040e5b0)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (c05daeb4)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (c05db11c)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (c00000000051b6e8)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (c00000000051b9c4)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (ffffffe0002b73e0)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffe0002b7596)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (ffffffff8134585a)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81345a84)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (ffffffff8133653a)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81336764)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (ffffffff8134332a)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81343554)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
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
In fs/crypto/keyring.c (ffffffff8135660a)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffff81356834)
Location: fs/crypto/fscrypt_private.h:395
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_drop_inode
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
</details>
</li>
</ul>

## Differences
