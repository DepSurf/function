# Function: <code>forget_all_cached_acls</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8126de80)
Location: fs/posix_acl.c:84
Inline: False
```
**Symbols:**

```
ffffffff8126de80-ffffffff8126df06: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812997b0)
Location: fs/posix_acl.c:87
Inline: False
```
**Symbols:**

```
ffffffff812997b0-ffffffff81299817: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812ae2d0)
Location: fs/posix_acl.c:87
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812ae2d0-ffffffff812ae337: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb7f0)
Location: fs/posix_acl.c:88
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812bb7f0-ffffffff812bb856: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812df0e0)
Location: fs/posix_acl.c:88
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff812df0e0-ffffffff812df146: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130b070)
Location: fs/posix_acl.c:88
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8130b070-ffffffff8130b0e2: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81320850)
Location: fs/posix_acl.c:88
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81320850-ffffffff813208c2: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81348100)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81348100-ffffffff81348172: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813603a0)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813603a0-ffffffff81360412: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a5f10)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813a5f10-ffffffff813a5fab: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b6c60)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813b6c60-ffffffff813b6cfb: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813bdcc0)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813bdcc0-ffffffff813bdd5b: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140daf0)
Location: fs/posix_acl.c:100
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8140daf0-ffffffff8140db8b: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81483080)
Location: fs/posix_acl.c:101
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81483080-ffffffff81483128: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81516310)
Location: fs/posix_acl.c:107
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81516310-ffffffff815163b8: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8154dc90)
Location: fs/posix_acl.c:108
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8154dc90-ffffffff8154dd3a: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81583ae0)
Location: fs/posix_acl.c:108
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_get_attr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81583ae0-ffffffff81583b8a: forget_all_cached_acls (STB_GLOBAL)
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
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff800010426700)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff800010426700-ffff800010426734: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05ef2f4)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c05ef2f4-c05ef320: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000535b60)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c000000000535b60-c000000000535c70: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c4a44)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe0002c4a44-ffffffe0002c4a7c: forget_all_cached_acls (STB_GLOBAL)
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
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81358980)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81358980-ffffffff813589f2: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349630)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81349630-ffffffff813496a2: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356450)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81356450-ffffffff813564c2: forget_all_cached_acls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void forget_all_cached_acls(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369b30)
Location: fs/posix_acl.c:89
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81369b30-ffffffff81369ba2: forget_all_cached_acls (STB_GLOBAL)
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
