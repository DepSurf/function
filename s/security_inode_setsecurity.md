# Function: <code>security_inode_setsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133dcc0)
Location: security/security.c:716
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff8133dcc0-ffffffff8133dd36: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373310)
Location: security/security.c:727
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff81373310-ffffffff8137339e: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389c40)
Location: security/security.c:736
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff81389c40-ffffffff81389cce: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f010)
Location: security/security.c:1341
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff8139f010-ffffffff8139f09b: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4ac0)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff813c4ac0-ffffffff813c4b55: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4e70)
Location: security/security.c:832
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff813f4e70-ffffffff813f4ef9: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81410240)
Location: security/security.c:1353
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff81410240-ffffffff814102c9: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d920)
Location: security/security.c:1366
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff8143d920-ffffffff8143d9a5: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457370)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff81457370-ffffffff814573f5: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa180)
Location: security/security.c:1554
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff814aa180-ffffffff814aa205: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7790)
Location: security/security.c:1556
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff814c7790-ffffffff814c7815: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cdc60)
Location: security/security.c:1607
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff814cdc60-ffffffff814cdce5: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526b70)
Location: security/security.c:1614
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff81526b70-ffffffff81526bf5: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bb5f0)
Location: security/security.c:1620
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff815bb5f0-ffffffff815bb693: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816673a0)
Location: security/security.c:1661
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff816673a0-ffffffff81667443: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169f990)
Location: security/security.c:2554
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff8169f990-ffffffff8169fa33: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc2f0)
Location: security/security.c:2628
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff816dc2f0-ffffffff816dc393: security_inode_setsecurity (STB_GLOBAL)
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
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542ee8)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffff800010542ee8-ffff800010542f88: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8e88)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
c06f8e88-c06f8f1c: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696a20)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
c000000000696a20-c000000000696b28: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f5ac)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffe00039f5ac-ffffffe00039f622: security_inode_setsecurity (STB_GLOBAL)
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
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f950)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff8144f950-ffffffff8144f9d5: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814403a0)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff814403a0-ffffffff81440425: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b9f0)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff8144b9f0-ffffffff8144ba75: security_inode_setsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_setsecurity(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462dc0)
Location: security/security.c:1406
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_setxattr_noperm
```
**Symbols:**

```
ffffffff81462dc0-ffffffff81462e45: security_inode_setsecurity (STB_GLOBAL)
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
