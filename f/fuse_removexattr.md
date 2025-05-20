# Function: <code>fuse_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_removexattr(struct dentry *entry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81312560)
Location: fs/fuse/dir.c:1842
Inline: False
```
**Symbols:**

```
ffffffff81312560-ffffffff81312665: fuse_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_removexattr(struct dentry *entry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81346a30)
Location: fs/fuse/dir.c:1870
Inline: False
```
**Symbols:**

```
ffffffff81346a30-ffffffff81346b38: fuse_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81367b20)
Location: fs/fuse/xattr.c:176
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81367b20-ffffffff81367c10: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8137c0f0)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8137c0f0-ffffffff8137c1d7: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813a0f90)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813a0f90-ffffffff813a1077: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813d0370)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813d0370-ffffffff813d0459: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813e98e0)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff813e98e0-ffffffff813e99c9: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81415a40)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81415a40-ffffffff81415b30: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8142f880)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8142f880-ffffffff8142f972: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8147f6f0)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8147f6f0-ffffffff8147f7e0: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149ad80)
Location: fs/fuse/xattr.c:154
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8149ad80-ffffffff8149ae74: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149ffd0)
Location: fs/fuse/xattr.c:157
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8149ffd0-ffffffff814a00c4: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814f7fe0)
Location: fs/fuse/xattr.c:157
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814f7fe0-ffffffff814f80d4: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81588040)
Location: fs/fuse/xattr.c:156
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81588040-ffffffff8158812f: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8162e3c0)
Location: fs/fuse/xattr.c:156
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8162e3c0-ffffffff8162e4af: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81666600)
Location: fs/fuse/xattr.c:156
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81666600-ffffffff816666ea: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff816a08e0)
Location: fs/fuse/xattr.c:156
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff816a08e0-ffffffff816a09ca: fuse_removexattr (STB_GLOBAL)
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
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffff800010514220)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffff800010514220-ffff800010514320: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c06cf088)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c06cf088-c06cf18c: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c00000000065c4c0)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
c00000000065c4c0-c00000000065c5fc: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (ffffffe00037da1c)
Location: fs/fuse/xattr.c:151
Inline: True
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffe00037da1c-ffffffe00037da52: fuse_removexattr.part.0 (STB_LOCAL)
ffffffe00037de46-ffffffe00037df2c: fuse_removexattr (STB_GLOBAL)
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
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81427e60)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81427e60-ffffffff81427f52: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814188e0)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff814188e0-ffffffff814189d2: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81424000)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81424000-ffffffff814240f2: fuse_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_removexattr(struct inode *inode, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8143ae40)
Location: fs/fuse/xattr.c:151
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8143ae40-ffffffff8143af32: fuse_removexattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *entry</code>
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
