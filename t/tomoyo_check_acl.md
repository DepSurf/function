# Function: <code>tomoyo_check_acl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8136d6e0)
Location: security/tomoyo/domain.c:156
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8136d6e0-ffffffff8136d798: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813a3920)
Location: security/tomoyo/domain.c:156
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813a3920-ffffffff813a39de: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813ba4a0)
Location: security/tomoyo/domain.c:156
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813ba4a0-ffffffff813ba55e: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813d0d30)
Location: security/tomoyo/domain.c:158
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813d0d30-ffffffff813d0def: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813f71e0)
Location: security/tomoyo/domain.c:159
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813f71e0-ffffffff813f72a1: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814281b0)
Location: security/tomoyo/domain.c:159
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814281b0-ffffffff81428277: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81444a60)
Location: security/tomoyo/domain.c:159
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81444a60-ffffffff81444b27: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81472740)
Location: security/tomoyo/domain.c:159
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81472740-ffffffff8147280d: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8148c4e0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8148c4e0-ffffffff8148c5ad: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e3780)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814e3780-ffffffff814e384d: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81500bb0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81500bb0-ffffffff81500c7d: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81507640)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81507640-ffffffff8150770e: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815647d0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff815647d0-ffffffff815648ca: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815fff80)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff815fff80-ffffffff8160006e: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff816b0e80)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff816b0e80-ffffffff816b0f6e: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff816e9890)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff816e9890-ffffffff816e9979: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff817265a0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff817265a0-ffffffff81726689: tomoyo_check_acl (STB_GLOBAL)
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
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffff80001057f8d0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffff80001057f8d0-ffff80001057f9fc: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0731df0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c0731df0-c0731f0c: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0000000006ecbd0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c0000000006ecbd0-c0000000006ecd68: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffe0003d0734)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffe0003d0734-ffffffe0003d0868: tomoyo_check_acl (STB_GLOBAL)
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
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81484ac0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81484ac0-ffffffff81484b8d: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814754e0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814754e0-ffffffff814755ad: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81480b60)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81480b60-ffffffff81480c2d: tomoyo_check_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_check_acl(struct tomoyo_request_info *r, bool (*check_entry)(struct tomoyo_request_info *, const struct tomoyo_acl_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814986d0)
Location: security/tomoyo/domain.c:161
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814986d0-ffffffff8149879d: tomoyo_check_acl (STB_GLOBAL)
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
