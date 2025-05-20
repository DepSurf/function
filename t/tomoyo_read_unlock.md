# Function: <code>tomoyo_read_unlock</code>

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
In security/tomoyo/common.c (ffffffff81f98e9b)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_check_profile
```
```
In security/tomoyo/file.c (ffffffff8136f460)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/tomoyo/mount.c (ffffffff81371751)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81371a5c)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372f7a)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813735ed)
Location: security/tomoyo/common.h:1107
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
In security/tomoyo/common.c (ffffffff813a1caa)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813a5f05)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813a7b61)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813a7e7c)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a924a)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a9a0d)
Location: security/tomoyo/common.h:1107
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
In security/tomoyo/common.c (ffffffff813b882a)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813bca85)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813be6f1)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813bea0c)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfdba)
Location: security/tomoyo/common.h:1107
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c057d)
Location: security/tomoyo/common.h:1107
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
In security/tomoyo/common.c (ffffffff813cf0de)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813d33e7)
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
In security/tomoyo/mount.c (ffffffff813d4ff1)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813d54ca)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d666f)
Location: security/tomoyo/common.h:1109
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6ef0)
Location: security/tomoyo/common.h:1109
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
In security/tomoyo/common.c (ffffffff813f558e)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813f98f7)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813fb501)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813fb8ca)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcb9f)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd420)
Location: security/tomoyo/common.h:1111
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
In security/tomoyo/common.c (ffffffff814264d6)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8142a7f8)
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
In security/tomoyo/mount.c (ffffffff8142c481)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8142c77b)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142dad1)
Location: security/tomoyo/common.h:1108
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142e302)
Location: security/tomoyo/common.h:1108
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
In security/tomoyo/common.c (ffffffff81442bd6)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814470c8)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81448dd1)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814490cb)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a421)
Location: security/tomoyo/common.h:1111
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144ac8d)
Location: security/tomoyo/common.h:1111
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
In security/tomoyo/common.c (ffffffff814707ae)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81474cdb)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81476a01)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81476ece)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81478200)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81478915)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff8148a56e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148ea7b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814907a1)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81490c6e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491f20)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81492635)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff814e16fe)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814e5d0b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814e7b21)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814e7ffe)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e92f0)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e9a25)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff814feb2e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8150310b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81504ea1)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150537e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81506615)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81506d45)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff815057ce)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81509cdb)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8150ba21)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150befe)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d155)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d885)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff815625ff)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff815671c7)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81569291)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81569a41)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ac9e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156b3d5)
Location: security/tomoyo/common.h:1121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void tomoyo_read_unlock(int idx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815fd6df)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81602d78)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81605005)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81605884)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606cf8)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816075dd)
Location: security/tomoyo/common.h:1120
Inline: True
```
**Symbols:**

```
ffffffff815f7150-ffffffff815f7189: tomoyo_read_unlock (STB_LOCAL)
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
In security/tomoyo/common.c (ffffffff816ae4cb)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816b3ef8)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816b6335)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816b6c74)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b8238)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b8d0d)
Location: security/tomoyo/common.h:1120
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
In security/tomoyo/common.c (ffffffff816e6efb)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816ec8b8)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816eed45)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816ef654)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c08)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f16e0)
Location: security/tomoyo/common.h:1120
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
In security/tomoyo/common.c (ffffffff81723c0b)
Location: security/tomoyo/common.h:1118
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81729688)
Location: security/tomoyo/common.h:1118
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8172bb15)
Location: security/tomoyo/common.h:1118
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8172c424)
Location: security/tomoyo/common.h:1118
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172d9d8)
Location: security/tomoyo/common.h:1118
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172e4b0)
Location: security/tomoyo/common.h:1118
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
In security/tomoyo/common.c (ffff80001057d9d4)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffff8000105823e8)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffff8000105849f8)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffff8000105850a0)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffff8000105866c4)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587234)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (c072ff50)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0734318)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0736470)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0736a5c)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0738098)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0738a14)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (c0000000006e97f4)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0000000006f0ccc)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0000000006f3dd4)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0000000006f4608)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6784)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0000000006f7438)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffe0003ced2c)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffe0003d2922)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffe0003d48fe)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffe0003d4e12)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d606c)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d6986)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff81482b4e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148705b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81488d81)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8148924e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a500)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148ac15)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff8147356e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81477a7b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814797a1)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81479c6e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147af20)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b635)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff8147ebee)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814830fb)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81484e21)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814852ee)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814865a0)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81486cb5)
Location: security/tomoyo/common.h:1121
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
In security/tomoyo/common.c (ffffffff8149671e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8149ac8b)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8149c961)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8149ce2e)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e0e0)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e7f5)
Location: security/tomoyo/common.h:1121
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
