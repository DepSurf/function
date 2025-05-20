# Function: <code>tomoyo_read_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81f98d99)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_check_profile
```
```
In security/tomoyo/file.c (ffffffff8136f380)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/tomoyo/mount.c (ffffffff8137172d)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81371a36)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372f23)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813735d6)
Location: security/tomoyo/common.h:1095
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813a1c2a)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813a5dec)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813a7b3d)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813a7e58)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a91f3)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a99f6)
Location: security/tomoyo/common.h:1095
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
In security/tomoyo/common.c (ffffffff813b87aa)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813bc96c)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813be6cd)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813be9e8)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfd63)
Location: security/tomoyo/common.h:1095
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c0566)
Location: security/tomoyo/common.h:1095
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
In security/tomoyo/common.c (ffffffff813cf056)
Location: security/tomoyo/common.h:1097
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813d32b3)
Location: security/tomoyo/common.h:1097
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813d4fcd)
Location: security/tomoyo/common.h:1097
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813d53b5)
Location: security/tomoyo/common.h:1097
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d6626)
Location: security/tomoyo/common.h:1097
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6ed9)
Location: security/tomoyo/common.h:1097
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
In security/tomoyo/common.c (ffffffff813f5506)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813f97c3)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813fb4dd)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813fb7b5)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcb56)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd409)
Location: security/tomoyo/common.h:1099
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
In security/tomoyo/common.c (ffffffff81426445)
Location: security/tomoyo/common.h:1096
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8142a7c5)
Location: security/tomoyo/common.h:1096
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8142c44d)
Location: security/tomoyo/common.h:1096
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8142c73f)
Location: security/tomoyo/common.h:1096
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142da81)
Location: security/tomoyo/common.h:1096
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142e2de)
Location: security/tomoyo/common.h:1096
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
In security/tomoyo/common.c (ffffffff81442b45)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81447095)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81448d9d)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8144908f)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a3d1)
Location: security/tomoyo/common.h:1099
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144ac69)
Location: security/tomoyo/common.h:1099
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
In security/tomoyo/common.c (ffffffff81470715)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81474ca8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814769d0)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81476e9d)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814781a3)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814788fe)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff8148a4d5)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148ea48)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81490770)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81490c3d)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491ec3)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149261e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff814e1665)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814e5cd8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814e7af0)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814e7fcd)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e9293)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e9a0e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff814fea95)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff815030d8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81504e70)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150534d)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff815065bf)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81506d2e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff81505735)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81509ca8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8150b9f0)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150becd)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d0ff)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d86e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff81562555)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81567194)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81569260)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff815699fd)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ac33)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156b3be)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff815fd635)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81602d45)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81604fdf)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81605843)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606c7f)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816075c6)
Location: security/tomoyo/common.h:1108
Inline: True
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
In security/tomoyo/common.c (ffffffff816ae425)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816b3ec5)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816b630f)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816b6c33)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b81bf)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b8cf6)
Location: security/tomoyo/common.h:1108
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
In security/tomoyo/common.c (ffffffff816e6e55)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816ec885)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816eed1f)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816ef613)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0b8f)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f16c9)
Location: security/tomoyo/common.h:1108
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
In security/tomoyo/common.c (ffffffff81723b65)
Location: security/tomoyo/common.h:1106
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81729655)
Location: security/tomoyo/common.h:1106
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8172baef)
Location: security/tomoyo/common.h:1106
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8172c3e3)
Location: security/tomoyo/common.h:1106
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172d95f)
Location: security/tomoyo/common.h:1106
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172e499)
Location: security/tomoyo/common.h:1106
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
In security/tomoyo/common.c (ffff80001057d938)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffff8000105823c0)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffff8000105849c8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffff800010585058)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffff800010586664)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001058720c)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (c072fe98)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c07342ec)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0736440)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0736a18)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0738038)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c07389f4)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (c0000000006e96cc)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0000000006f0c90)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0000000006f3d98)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0000000006f45bc)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6700)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0000000006f740c)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffe0003cec94)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffe0003d28e2)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffe0003d48d8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffe0003d4de2)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d600c)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d696a)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff81482ab5)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81487028)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81488d50)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8148921d)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a4a3)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148abfe)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff814734d5)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81477a48)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81479770)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81479c3d)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147aec3)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b61e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff8147eb55)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814830c8)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81484df0)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814852bd)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81486543)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81486c9e)
Location: security/tomoyo/common.h:1109
Inline: True
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
In security/tomoyo/common.c (ffffffff81496685)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8149ac58)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8149c930)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8149cdfd)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e083)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e7de)
Location: security/tomoyo/common.h:1109
Inline: True
```
</details>
</li>
</ul>

## Differences
