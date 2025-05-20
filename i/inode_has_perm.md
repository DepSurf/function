# Function: <code>inode_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813428e1)
Location: security/selinux/hooks.c:1635
Inline: True
Inline callers:
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137d4fe)
Location: security/selinux/hooks.c:1706
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81393f48)
Location: security/selinux/hooks.c:1714
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4a40)
Location: security/selinux/hooks.c:1703
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff813a4a40-ffffffff813a4a7f: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca6a0)
Location: security/selinux/hooks.c:1707
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff813ca6a0-ffffffff813ca6df: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb3b0)
Location: security/selinux/hooks.c:1808
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff813fb3b0-ffffffff813fb3e9: inode_has_perm.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415980)
Location: security/selinux/hooks.c:1622
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81415980-ffffffff814159d2: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814433b0)
Location: security/selinux/hooks.c:1666
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814433b0-ffffffff81443403: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145cf00)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8145cf00-ffffffff8145cf53: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b01b0)
Location: security/selinux/hooks.c:1621
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814b01b0-ffffffff814b0203: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cd8c0)
Location: security/selinux/hooks.c:1630
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814cd8c0-ffffffff814cd913: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d3ec0)
Location: security/selinux/hooks.c:1689
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814d3ec0-ffffffff814d3f13: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152cb80)
Location: security/selinux/hooks.c:1681
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8152cb80-ffffffff8152cbd3: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c2f10)
Location: security/selinux/hooks.c:1619
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff815c2f10-ffffffff815c2f85: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166f7d0)
Location: security/selinux/hooks.c:1618
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff8166f7d0-ffffffff8166f845: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a7d50)
Location: security/selinux/hooks.c:1630
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff816a7d50-ffffffff816a7dbf: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e47b0)
Location: security/selinux/hooks.c:1672
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff816e47b0-ffffffff816e4822: inode_has_perm (STB_LOCAL)
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
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010549c28)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffff800010549c28-ffff800010549cc4: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff9c0)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
c06ff9c0-c06ffa44: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a13d0)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
c0000000006a13d0-c0000000006a1468: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a499e)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffe0003a499e-ffffffe0003a4a1e: inode_has_perm (STB_LOCAL)
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
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814554e0)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff814554e0-ffffffff81455533: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445f20)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81445f20-ffffffff81445f73: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81451580)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81451580-ffffffff814515d3: inode_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inode_has_perm(const struct cred *cred, struct inode *inode, u32 perms, struct common_audit_data *adp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81468630)
Location: security/selinux/hooks.c:1668
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:file_has_perm
```
**Symbols:**

```
ffffffff81468630-ffffffff81468683: inode_has_perm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
