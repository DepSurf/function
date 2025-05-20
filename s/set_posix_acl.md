# Function: <code>set_posix_acl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812995e0)
Location: fs/posix_acl.c:834
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff812995e0-ffffffff81299680: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812ae100)
Location: fs/posix_acl.c:866
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff812ae100-ffffffff812ae1a0: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb640)
Location: fs/posix_acl.c:857
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff812bb640-ffffffff812bb6e2: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff812def30)
Location: fs/posix_acl.c:857
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff812def30-ffffffff812defd8: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8130af60)
Location: fs/posix_acl.c:857
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff8130af60-ffffffff8130b006: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813207a0)
Location: fs/posix_acl.c:857
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813207a0-ffffffff81320846: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81348040)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81348040-ffffffff813480ff: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813602e0)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813602e0-ffffffff8136039f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813a5c60)
Location: fs/posix_acl.c:861
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813a5c60-ffffffff813a5d1f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813b69a0)
Location: fs/posix_acl.c:861
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813b69a0-ffffffff813b6a5f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_posix_acl(struct user_namespace *mnt_userns, struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813bd9f0)
Location: fs/posix_acl.c:903
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813bd9f0-ffffffff813bdabb: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_posix_acl(struct user_namespace *mnt_userns, struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8140d7b0)
Location: fs/posix_acl.c:914
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff8140d7b0-ffffffff8140d87b: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_posix_acl(struct user_namespace *mnt_userns, struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81482a60)
Location: fs/posix_acl.c:928
Inline: False
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81482a60-ffffffff81482b4a: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_posix_acl(struct user_namespace *mnt_userns, struct dentry *dentry, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff815157f0)
Location: fs/posix_acl.c:937
Inline: False
Direct callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff815157f0-ffffffff815158d8: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_posix_acl(struct mnt_idmap *idmap, struct dentry *dentry, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff8154d2d0)
Location: fs/posix_acl.c:936
Inline: False
Direct callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff8154d2d0-ffffffff8154d3b8: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_posix_acl(struct mnt_idmap *idmap, struct dentry *dentry, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81583100)
Location: fs/posix_acl.c:936
Inline: False
Direct callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
**Symbols:**

```
ffffffff81583100-ffffffff815831e8: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffff800010426568)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffff800010426568-ffff800010426638: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c05ef184)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
c05ef184-c05ef248: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (c000000000535940)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
c000000000535940-c000000000535a80: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c574e)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffe0002c574e-ffffffe0002c57ee: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff813588c0)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff813588c0-ffffffff8135897f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81349570)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81349570-ffffffff8134962f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81356390)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81356390-ffffffff8135644f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_posix_acl(struct inode *inode, int type, struct posix_acl *acl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/posix_acl.c (ffffffff81369a70)
Location: fs/posix_acl.c:858
Inline: True
Direct callers:
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_set
```
**Symbols:**

```
ffffffff81369a70-ffffffff81369b2f: set_posix_acl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>inode, type, acl</code> ➡️ <code>mnt_userns, inode, type, acl</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
</ul>
</details>
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
