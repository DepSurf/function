# Function: <code>tomoyo_fill_path_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81374530)
Location: security/tomoyo/util.c:661
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff81374530-ffffffff813745ec: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aa930)
Location: security/tomoyo/util.c:661
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff813aa930-ffffffff813aa9fe: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c14b0)
Location: security/tomoyo/util.c:661
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff813c14b0-ffffffff813c157e: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d7e30)
Location: security/tomoyo/util.c:663
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff813d7e30-ffffffff813d7ef5: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe280)
Location: security/tomoyo/util.c:643
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff813fe280-ffffffff813fe345: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142f180)
Location: security/tomoyo/util.c:643
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8142f180-ffffffff8142f240: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144bba0)
Location: security/tomoyo/util.c:643
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8144bba0-ffffffff8144bc60: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814798f0)
Location: security/tomoyo/util.c:654
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff814798f0-ffffffff814799b6: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814935f0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff814935f0-ffffffff814936b6: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814ea9b0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff814ea9b0-ffffffff814eaa88: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507db0)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff81507db0-ffffffff81507e88: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150e930)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8150e930-ffffffff8150ea08: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c480)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8156c480-ffffffff8156c558: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81608800)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff81608800-ffffffff816088f0: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816ba0a0)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff816ba0a0-ffffffff816ba190: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2a40)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff816f2a40-ffffffff816f2b30: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172f800)
Location: security/tomoyo/util.c:677
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/condition.c:tomoyo_scan_bprm
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8172f800-ffffffff8172f8f0: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010588900)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffff800010588900-ffff800010588a18: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0739d2c)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
c0739d2c-c0739e60: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f8ff0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
c0000000006f8ff0-c0000000006f915c: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d7918)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffe0003d7918-ffffffe0003d79fc: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148bbd0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8148bbd0-ffffffff8148bc96: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c5f0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8147c5f0-ffffffff8147c6b6: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487c70)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff81487c70-ffffffff81487d36: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_fill_path_info(struct tomoyo_path_info *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149f7b0)
Location: security/tomoyo/util.c:655
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - security/tomoyo/util.c:tomoyo_find_domain
```
**Symbols:**

```
ffffffff8149f7b0-ffffffff8149f876: tomoyo_fill_path_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
