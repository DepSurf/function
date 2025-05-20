# Function: <code>file_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81342870)
Location: security/selinux/hooks.c:1704
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
```
**Symbols:**

```
ffffffff81342870-ffffffff81342929: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81377bf0)
Location: security/selinux/hooks.c:1777
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff81377bf0-ffffffff81377ca9: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138e6e0)
Location: security/selinux/hooks.c:1785
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff8138e6e0-ffffffff8138e78b: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4a80)
Location: security/selinux/hooks.c:1774
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff813a4a80-ffffffff813a4b29: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cddd0)
Location: security/selinux/hooks.c:1782
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff813cddd0-ffffffff813cde95: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb490)
Location: security/selinux/hooks.c:1884
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff813fb490-ffffffff813fb54e: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81417940)
Location: security/selinux/hooks.c:1698
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff81417940-ffffffff81417a0d: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445580)
Location: security/selinux/hooks.c:1742
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff81445580-ffffffff81445650: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145f110)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff8145f110-ffffffff8145f1e0: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b2110)
Location: security/selinux/hooks.c:1697
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff814b2110-ffffffff814b21e0: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf490)
Location: security/selinux/hooks.c:1706
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff814cf490-ffffffff814cf560: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5bc0)
Location: security/selinux/hooks.c:1765
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff814d5bc0-ffffffff814d5c90: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152e700)
Location: security/selinux/hooks.c:1757
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff8152e700-ffffffff8152e7d0: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c3060)
Location: security/selinux/hooks.c:1695
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff815c3060-ffffffff815c315f: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166f940)
Location: security/selinux/hooks.c:1694
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff8166f940-ffffffff8166fa3f: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a7ea0)
Location: security/selinux/hooks.c:1705
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff816a7ea0-ffffffff816a7f97: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e4910)
Location: security/selinux/hooks.c:1745
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff816e4910-ffffffff816e4a0d: file_has_perm (STB_LOCAL)
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
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054c2b0)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffff80001054c2b0-ffff80001054c3a8: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c070255c)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
c070255c-c070265c: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4c00)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
c0000000006a4c00-c0000000006a4d30: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a696e)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffe0003a696e-ffffffe0003a6a1c: file_has_perm (STB_LOCAL)
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
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814576f0)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff814576f0-ffffffff814577c0: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448120)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff81448120-ffffffff814481f0: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81453790)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff81453790-ffffffff81453860: file_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int file_has_perm(const struct cred *cred, struct file *file, u32 av);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146b290)
Location: security/selinux/hooks.c:1744
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:match_file
```
**Symbols:**

```
ffffffff8146b290-ffffffff8146b360: file_has_perm (STB_LOCAL)
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
