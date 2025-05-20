# Function: <code>simple_xattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81233490)
Location: fs/xattr.c:941
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setxattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff81233490-ffffffff812334ae: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125b9d0)
Location: fs/xattr.c:900
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_iop_removexattr
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff8125b9d0-ffffffff8125bb43: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126ef80)
Location: fs/xattr.c:898
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff8126ef80-ffffffff8126f0f3: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127c790)
Location: fs/xattr.c:895
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff8127c790-ffffffff8127c8ef: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129f230)
Location: fs/xattr.c:896
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff8129f230-ffffffff8129f38f: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5d90)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff812c5d90-ffffffff812c5eef: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812daf90)
Location: fs/xattr.c:893
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff812daf90-ffffffff812db0e6: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f9600)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff812f9600-ffffffff812f975b: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130b230)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff8130b230-ffffffff8130b38b: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81344a00)
Location: fs/xattr.c:965
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff81344a00-ffffffff81344b93: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81350cf0)
Location: fs/xattr.c:997
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff81350cf0-ffffffff81350e83: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813579e0)
Location: fs/xattr.c:1026
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff813579e0-ffffffff81357b73: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a5e10)
Location: fs/xattr.c:1027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff813a5e10-ffffffff813a5fa3: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8142a1a0)
Location: fs/xattr.c:1079
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff8142a1a0-ffffffff8142a340: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b72a0)
Location: fs/xattr.c:1182
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff814b72a0-ffffffff814b7472: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags, ssize_t *removed_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814ec100)
Location: fs/xattr.c:1186
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff814ec100-ffffffff814ec2d2: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct simple_xattr *simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81520020)
Location: fs/xattr.c:1206
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_user_xattr_set
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
```
**Symbols:**

```
ffffffff81520020-ffffffff815201b5: simple_xattr_set (STB_GLOBAL)
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
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bf5e8)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffff8000103bf5e8-ffff8000103bf7a8: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059c448)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
c059c448-c059c598: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bdd10)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
c0000000004bdd10-c0000000004be13c: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027ffa0)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffe00027ffa0-ffffffe000280106: simple_xattr_set (STB_GLOBAL)
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
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81303810)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff81303810-ffffffff8130396b: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f4430)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff812f4430-ffffffff812f458b: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301600)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff81301600-ffffffff8130175b: simple_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int simple_xattr_set(struct simple_xattrs *xattrs, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81312940)
Location: fs/xattr.c:894
Inline: False
Direct callers:
  - mm/shmem.c:shmem_xattr_handler_set
  - fs/kernfs/inode.c:kernfs_xattr_set
```
**Symbols:**

```
ffffffff81312940-ffffffff81312a9a: simple_xattr_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>ssize_t *removed_size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t *removed_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct simple_xattr *</code>
</li>
</ul>
</details>
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
