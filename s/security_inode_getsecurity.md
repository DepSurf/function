# Function: <code>security_inode_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_getsecurity(const struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133dc50)
Location: security/security.c:708
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff8133dc50-ffffffff8133dcb7: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373290)
Location: security/security.c:709
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff81373290-ffffffff81373308: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389bc0)
Location: security/security.c:718
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff81389bc0-ffffffff81389c38: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139ef90)
Location: security/security.c:1323
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff8139ef90-ffffffff8139f008: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4a40)
Location: security/security.c:1272
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff813c4a40-ffffffff813c4abe: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4df0)
Location: security/security.c:814
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff813f4df0-ffffffff813f4e66: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814101c0)
Location: security/security.c:1335
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814101c0-ffffffff81410236: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d8a0)
Location: security/security.c:1348
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8143d8a0-ffffffff8143d914: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814572f0)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814572f0-ffffffff81457364: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa100)
Location: security/security.c:1536
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814aa100-ffffffff814aa174: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7710)
Location: security/security.c:1538
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814c7710-ffffffff814c7784: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cdbd0)
Location: security/security.c:1587
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814cdbd0-ffffffff814cdc5d: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526ae0)
Location: security/security.c:1594
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff81526ae0-ffffffff81526b6d: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bb530)
Location: security/security.c:1600
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff815bb530-ffffffff815bb5ed: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816672d0)
Location: security/security.c:1641
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff816672d0-ffffffff8166738d: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169f8c0)
Location: security/security.c:2518
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff8169f8c0-ffffffff8169f97d: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc220)
Location: security/security.c:2592
Inline: False
Direct callers:
  - fs/xattr.c:xattr_getsecurity
  - fs/xattr.c:xattr_getsecurity
```
**Symbols:**

```
ffffffff816dc220-ffffffff816dc2dd: security_inode_getsecurity (STB_GLOBAL)
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
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542e50)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffff800010542e50-ffff800010542ee8: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8e10)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
c06f8e10-c06f8e88: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696910)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
c000000000696910-c000000000696a18: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f53e)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffe00039f53e-ffffffe00039f5ac: security_inode_getsecurity (STB_GLOBAL)
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
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f8d0)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8144f8d0-ffffffff8144f944: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440320)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff81440320-ffffffff81440394: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b970)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8144b970-ffffffff8144b9e4: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462d40)
Location: security/security.c:1388
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff81462d40-ffffffff81462db4: security_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
</li>
</ul>
</details>
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
<code>inode, name, buffer, alloc</code> ➡️ <code>mnt_userns, inode, name, buffer, alloc</code>
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
