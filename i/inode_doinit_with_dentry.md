# Function: <code>inode_doinit_with_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81343540)
Location: security/selinux/hooks.c:1308
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81343540-ffffffff81343baa: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813782c0)
Location: security/selinux/hooks.c:1379
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff813782c0-ffffffff8137894c: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138eda0)
Location: security/selinux/hooks.c:1381
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff8138eda0-ffffffff8138f321: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a5010)
Location: security/selinux/hooks.c:1429
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff813a5010-ffffffff813a55a4: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cab10)
Location: security/selinux/hooks.c:1433
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff813cab10-ffffffff813cb0aa: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1518
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff813fecf0-ffffffff813ff280: inode_doinit_with_dentry (STB_LOCAL)
ffffffff81402b11-ffffffff81402b9c: inode_doinit_with_dentry.cold.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1333
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff8141adf0-ffffffff8141b3af: inode_doinit_with_dentry (STB_LOCAL)
ffffffff8141e6ba-ffffffff8141e745: inode_doinit_with_dentry.cold.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814488e0)
Location: security/selinux/hooks.c:1429
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff814488e0-ffffffff81448d89: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81462470)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff81462470-ffffffff81462919: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b63b0)
Location: security/selinux/hooks.c:1382
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
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
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff814b63b0-ffffffff814b686e: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4090)
Location: security/selinux/hooks.c:1383
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
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
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff814d4090-ffffffff814d4568: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814da640)
Location: security/selinux/hooks.c:1442
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
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
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff814da640-ffffffff814dab43: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1434
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff81533540-ffffffff81533a4f: inode_doinit_with_dentry (STB_LOCAL)
ffffffff81cd3ab4-ffffffff81cd3ad7: inode_doinit_with_dentry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1372
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff815c9d20-ffffffff815ca239: inode_doinit_with_dentry (STB_LOCAL)
ffffffff81e86bed-ffffffff81e86c0a: inode_doinit_with_dentry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1371
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff81676f40-ffffffff81677459: inode_doinit_with_dentry (STB_LOCAL)
ffffffff820736c5-ffffffff820736e2: inode_doinit_with_dentry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1382
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff816af230-ffffffff816af74f: inode_doinit_with_dentry (STB_LOCAL)
ffffffff820f32be-ffffffff820f32db: inode_doinit_with_dentry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1424
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
```
**Symbols:**

```
ffffffff816ec1a0-ffffffff816ec6bf: inode_doinit_with_dentry (STB_LOCAL)
ffffffff821d0420-ffffffff821d043d: inode_doinit_with_dentry.cold (STB_LOCAL)
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
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105501f0)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffff8000105501f0-ffff800010550728: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0702e08)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
c0702e08-c0703288: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a58f0)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
c0000000006a58f0-c0000000006a5f74: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a97f6)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffe0003a97f6-ffffffe0003a9c54: inode_doinit_with_dentry (STB_LOCAL)
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
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145aa50)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff8145aa50-ffffffff8145aef9: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144b480)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff8144b480-ffffffff8144b929: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81456af0)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff81456af0-ffffffff81456f99: inode_doinit_with_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inode_doinit_with_dentry(struct inode *inode, struct dentry *opt_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146ba60)
Location: security/selinux/hooks.c:1431
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_d_instantiate
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
**Symbols:**

```
ffffffff8146ba60-ffffffff8146bf24: inode_doinit_with_dentry (STB_LOCAL)
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
