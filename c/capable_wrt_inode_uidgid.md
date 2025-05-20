# Function: <code>capable_wrt_inode_uidgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a360)
Location: kernel/capability.c:442
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/attr.c:setattr_copy
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
```
**Symbols:**

```
ffffffff8108a360-ffffffff8108a3c3: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d300)
Location: kernel/capability.c:468
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:should_remove_suid
  - fs/attr.c:setattr_copy
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
```
**Symbols:**

```
ffffffff8108d300-ffffffff8108d368: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092730)
Location: kernel/capability.c:482
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:should_remove_suid
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
```
**Symbols:**

```
ffffffff81092730-ffffffff8109277d: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f870)
Location: kernel/capability.c:482
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:should_remove_suid
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff8108f870-ffffffff8108f8bd: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096730)
Location: kernel/capability.c:483
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:should_remove_suid
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81096730-ffffffff8109677d: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099c40)
Location: kernel/capability.c:483
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81099c40-ffffffff81099c94: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1fd0)
Location: kernel/capability.c:485
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810a1fd0-ffffffff810a2019: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6a00)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810a6a00-ffffffff810a6a4c: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810acfe0)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810acfe0-ffffffff810ad02c: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4850)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810b4850-ffffffff810b48b1: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afa50)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810afa50-ffffffff810afab1: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool capable_wrt_inode_uidgid(struct user_namespace *mnt_userns, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:504
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81bcdadc-ffffffff81bcdaec: capable_wrt_inode_uidgid.cold (STB_LOCAL)
ffffffff810b1220-ffffffff810b1288: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool capable_wrt_inode_uidgid(struct user_namespace *mnt_userns, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:504
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81ca45c3-ffffffff81ca45d3: capable_wrt_inode_uidgid.cold (STB_LOCAL)
ffffffff810c32e0-ffffffff810c3348: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool capable_wrt_inode_uidgid(struct user_namespace *mnt_userns, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/capability.c (0)
Location: kernel/capability.c:505
Inline: False
Direct callers:
  - fs/namei.c:__check_sticky
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81e53e46-ffffffff81e53e56: capable_wrt_inode_uidgid.cold (STB_LOCAL)
ffffffff810da820-ffffffff810da893: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(struct user_namespace *mnt_userns, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa8f0)
Location: kernel/capability.c:505
Inline: False
Direct callers:
  - fs/namei.c:__check_sticky
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810fa8f0-ffffffff810fa96f: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(struct mnt_idmap *idmap, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106930)
Location: kernel/capability.c:493
Inline: False
Direct callers:
  - fs/namei.c:__check_sticky
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81106930-ffffffff811069af: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(struct mnt_idmap *idmap, const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81110280)
Location: kernel/capability.c:493
Inline: False
Direct callers:
  - fs/namei.c:__check_sticky
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/fuse/acl.c:fuse_set_acl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81110280-ffffffff811102ff: capable_wrt_inode_uidgid (STB_GLOBAL)
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
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010106820)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffff800010106820-ffff800010106888: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c036151c)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
c036151c-c0361570: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014dc00)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
c00000000014dc00-c00000000014dc80: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb592)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffe0000cb592-ffffffe0000cb5e6: capable_wrt_inode_uidgid (STB_GLOBAL)
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
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a7350)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810a7350-ffffffff810a739c: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095d30)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff81095d30-ffffffff81095d7c: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a68b0)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810a68b0-ffffffff810a68fc: capable_wrt_inode_uidgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool capable_wrt_inode_uidgid(const struct inode *inode, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ae9e0)
Location: kernel/capability.c:502
Inline: False
Direct callers:
  - fs/namei.c:may_delete
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff810ae9e0-ffffffff810aea2c: capable_wrt_inode_uidgid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, cap</code> ➡️ <code>mnt_userns, inode, cap</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
