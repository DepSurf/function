# Function: <code>xattr_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81231e70)
Location: fs/xattr.c:146
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff81231e70-ffffffff81231f24: xattr_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125a390)
Location: fs/xattr.c:154
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8125a390-ffffffff8125a444: xattr_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126da90)
Location: fs/xattr.c:233
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8126da90-ffffffff8126db44: xattr_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b2b0)
Location: fs/xattr.c:233
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8127b2b0-ffffffff8127b368: xattr_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129dd40)
Location: fs/xattr.c:234
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8129dd40-ffffffff8129dded: xattr_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c45cb)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d97cb)
Location: fs/xattr.c:233
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7d59)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309959)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343d61)
Location: fs/xattr.c:271
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813500d1)
Location: fs/xattr.c:309
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356c1d)
Location: fs/xattr.c:319
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a56dd)
Location: fs/xattr.c:319
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428d84)
Location: fs/xattr.c:321
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4a60)
Location: fs/xattr.c:341
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814b4a60-ffffffff814b4b1e: xattr_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9ac0)
Location: fs/xattr.c:339
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff814e9ac0-ffffffff814e9b7e: xattr_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t xattr_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151d960)
Location: fs/xattr.c:339
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
```
**Symbols:**

```
ffffffff8151d960-ffffffff8151da1e: xattr_getsecurity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bdb44)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b03c)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bbac0)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027ecf4)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301f39)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2b59)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ffd29)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311069)
Location: fs/xattr.c:234
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
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
