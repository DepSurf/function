# Function: <code>tomoyo_supervisor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8136aac0)
Location: security/tomoyo/common.c:1995
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff8136aac0-ffffffff8136af10: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813a0a90)
Location: security/tomoyo/common.c:1995
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff813a0a90-ffffffff813a112e: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b7620)
Location: security/tomoyo/common.c:1995
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff813b7620-ffffffff813b7cab: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813cdf30)
Location: security/tomoyo/common.c:1995
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff813cdf30-ffffffff813ce56e: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f43d0)
Location: security/tomoyo/common.c:1996
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff813f43d0-ffffffff813f4a0f: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81425340)
Location: security/tomoyo/common.c:1996
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81425340-ffffffff81425975: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814419b0)
Location: security/tomoyo/common.c:1997
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff814419b0-ffffffff81442017: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8146f580)
Location: security/tomoyo/common.c:2057
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff8146f580-ffffffff8146fba9: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814893b0)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff814893b0-ffffffff814899af: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814e0a30)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff814e0a30-ffffffff814e0e76: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fde60)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff814fde60-ffffffff814fe2a6: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81504a20)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81504a20-ffffffff81504e68: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81cd5a4b-ffffffff81cd5a60: tomoyo_supervisor.cold (STB_LOCAL)
ffffffff81561890-ffffffff81561d3e: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2050
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81e88856-ffffffff81e8886b: tomoyo_supervisor.cold (STB_LOCAL)
ffffffff815fc8c0-ffffffff815fcda5: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2050
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff820743e5-ffffffff820743fa: tomoyo_supervisor.cold (STB_LOCAL)
ffffffff816ad660-ffffffff816adb2d: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2050
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff820f3f6e-ffffffff820f3f83: tomoyo_supervisor.cold (STB_LOCAL)
ffffffff816e6080-ffffffff816e6542: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2051
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff821d13b3-ffffffff821d13c8: tomoyo_supervisor.cold (STB_LOCAL)
ffffffff81722d30-ffffffff817231f2: tomoyo_supervisor (STB_GLOBAL)
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
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff80001057c560)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffff80001057c560-ffff80001057cc34: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072ed88)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
c072ed88-c072f318: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e7900)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
c0000000006e7900-c0000000006e8120: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003cdd0e)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffe0003cdd0e-ffffffe0003ce2e4: tomoyo_supervisor (STB_GLOBAL)
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
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81481990)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81481990-ffffffff81481f8f: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814723b0)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff814723b0-ffffffff814729af: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147da30)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff8147da30-ffffffff8147e02f: tomoyo_supervisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_supervisor(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81495550)
Location: security/tomoyo/common.c:2059
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_env_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/mount.c:tomoyo_mount_acl
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_audit_inet_log
```
**Symbols:**

```
ffffffff81495550-ffffffff81495b40: tomoyo_supervisor (STB_GLOBAL)
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
