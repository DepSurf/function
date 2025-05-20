# Function: <code>fuse_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_setxattr(struct dentry *entry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81312670)
Location: fs/fuse/dir.c:1722
Inline: False
```
**Symbols:**

```
ffffffff81312670-ffffffff813127c3: fuse_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_setxattr(struct dentry *unused, struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81346de0)
Location: fs/fuse/dir.c:1729
Inline: False
```
**Symbols:**

```
ffffffff81346de0-ffffffff81346ffb: fuse_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81367570)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81367570-ffffffff81367765: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8137bc60)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8137bc60-ffffffff8137bd91: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813a0b00)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813a0b00-ffffffff813a0c31: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813cfee0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813cfee0-ffffffff813d0013: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813e9450)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813e9450-ffffffff813e9583: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814155c0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814155c0-ffffffff814156f4: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8142f3f0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8142f3f0-ffffffff8142f526: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8147f260)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8147f260-ffffffff8147f394: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149a8d0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8149a8d0-ffffffff8149aa08: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149fb10)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8149fb10-ffffffff8149fc6c: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814f7b20)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814f7b20-ffffffff814f7c7c: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81587b10)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81587b10-ffffffff81587c85: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8162de40)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8162de40-ffffffff8162dfb5: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81666080)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81666080-ffffffff816661f0: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags, unsigned int extra_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff816a0360)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff816a0360-ffffffff816a04d0: fuse_setxattr (STB_GLOBAL)
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
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffff800010513d98)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffff800010513d98-ffff800010513ed0: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c06cec30)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c06cec30-c06ced60: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c00000000065bec0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c00000000065bec0-c00000000065c050: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (ffffffe00037d9e6)
Location: fs/fuse/xattr.c:14
Inline: True
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffe00037d9e6-ffffffe00037da1c: fuse_setxattr.part.0 (STB_LOCAL)
ffffffe00037da52-ffffffe00037db60: fuse_setxattr (STB_GLOBAL)
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
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814279d0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814279d0-ffffffff81427b06: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81418450)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81418450-ffffffff81418586: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81423b70)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81423b70-ffffffff81423ca6: fuse_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_setxattr(struct inode *inode, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8143a9b0)
Location: fs/fuse/xattr.c:14
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8143a9b0-ffffffff8143aae6: fuse_setxattr (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct dentry *unused</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, name, value, size, flags</code> ➡️ <code>unused, inode, name, value, size, flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dentry *unused</code>
</li>
<li>
<b>Param reordered. </b>
<code>unused, inode, name, value, size, flags</code> ➡️ <code>inode, name, value, size, flags</code>
</li>
</ul>
</details>
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
<code>unsigned int extra_flags</code>
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
