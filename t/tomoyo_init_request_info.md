# Function: <code>tomoyo_init_request_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813747a0)
Location: security/tomoyo/util.c:1002
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813747a0-ffffffff81374825: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aaba0)
Location: security/tomoyo/util.c:1002
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813aaba0-ffffffff813aac25: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c1720)
Location: security/tomoyo/util.c:1002
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813c1720-ffffffff813c17a5: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d80b0)
Location: security/tomoyo/util.c:1004
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813d80b0-ffffffff813d8145: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe500)
Location: security/tomoyo/util.c:984
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813fe500-ffffffff813fe595: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142f400)
Location: security/tomoyo/util.c:984
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8142f400-ffffffff8142f48b: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144be20)
Location: security/tomoyo/util.c:984
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8144be20-ffffffff8144beb6: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81479b80)
Location: security/tomoyo/util.c:996
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81479b80-ffffffff81479c13: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81493880)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81493880-ffffffff81493913: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814eac80)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814eac80-ffffffff814ead37: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81508080)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81508080-ffffffff81508137: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150ec00)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8150ec00-ffffffff8150ecb6: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c810)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8156c810-ffffffff8156c88a: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81608bf0)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81608bf0-ffffffff81608c79: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816ba4e0)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff816ba4e0-ffffffff816ba569: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2e70)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff816f2e70-ffffffff816f2ef9: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172fc30)
Location: security/tomoyo/util.c:1019
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8172fc30-ffffffff8172fcb9: tomoyo_init_request_info (STB_GLOBAL)
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
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010588ca0)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffff800010588ca0-ffff800010588d44: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c073a064)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c073a064-c073a0e4: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f9760)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c0000000006f9760-c0000000006f9840: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d7bae)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffe0003d7bae-ffffffe0003d7c40: tomoyo_init_request_info (STB_GLOBAL)
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
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148be60)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8148be60-ffffffff8148bef3: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c880)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8147c880-ffffffff8147c913: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487f00)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81487f00-ffffffff81487f93: tomoyo_init_request_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_init_request_info(struct tomoyo_request_info *r, struct tomoyo_domain_info *domain, const u8 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149fa40)
Location: security/tomoyo/util.c:997
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8149fa40-ffffffff8149fad3: tomoyo_init_request_info (STB_GLOBAL)
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
