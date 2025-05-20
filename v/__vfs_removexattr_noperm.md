# Function: <code>__vfs_removexattr_noperm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125add0)
Location: fs/xattr.c:289
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8125add0-ffffffff8125ae8f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e390)
Location: fs/xattr.c:398
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8126e390-ffffffff8126e42f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127bb90)
Location: fs/xattr.c:398
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8127bb90-ffffffff8127bc2d: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e630)
Location: fs/xattr.c:399
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8129e630-ffffffff8129e6cd: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c50e0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff812c50e0-ffffffff812c517f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812da2e0)
Location: fs/xattr.c:396
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff812da2e0-ffffffff812da37f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f88c0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff812f88c0-ffffffff812f895f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130a4f0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8130a4f0-ffffffff8130a58f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813433c0)
Location: fs/xattr.c:434
Inline: True
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff813433c0-ffffffff81343452: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f540)
Location: fs/xattr.c:472
Inline: True
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff8134f540-ffffffff8134f5e7: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356030)
Location: fs/xattr.c:488
Inline: True
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff81356030-ffffffff813560d7: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4550)
Location: fs/xattr.c:489
Inline: True
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff813a4550-ffffffff813a4607: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428647)
Location: fs/xattr.c:490
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff81428bf0-ffffffff81428cbe: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b5b67)
Location: fs/xattr.c:517
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff814b5180-ffffffff814b524e: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bdef8)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffff8000103bdef8-ffff8000103bdfc0: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b788)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
c059b788-c059b828: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bc950)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
c0000000004bc950-c0000000004bca58: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f380)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffe00027f380-ffffffe00027f416: __vfs_removexattr_noperm (STB_GLOBAL)
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
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81302ad0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81302ad0-ffffffff81302b6f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f36f0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff812f36f0-ffffffff812f378f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813008c0)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff813008c0-ffffffff8130095f: __vfs_removexattr_noperm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __vfs_removexattr_noperm(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311c00)
Location: fs/xattr.c:397
Inline: True
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81311c00-ffffffff81311c9f: __vfs_removexattr_noperm (STB_GLOBAL)
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
<code>dentry, name</code> ➡️ <code>mnt_userns, dentry, name</code>
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
