# Function: <code>simple_xattr_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812334d0)
Location: fs/xattr.c:965
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff812334d0-ffffffff81233596: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125bb50)
Location: fs/xattr.c:973
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8125bb50-ffffffff8125bc69: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126f100)
Location: fs/xattr.c:971
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8126f100-ffffffff8126f219: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127c8f0)
Location: fs/xattr.c:968
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8127c8f0-ffffffff8127ca0d: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129f390)
Location: fs/xattr.c:969
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8129f390-ffffffff8129f4ad: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5ef0)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff812c5ef0-ffffffff812c6016: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812db0f0)
Location: fs/xattr.c:966
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff812db0f0-ffffffff812db220: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f9760)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff812f9760-ffffffff812f988a: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130b390)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8130b390-ffffffff8130b4ba: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81344ba0)
Location: fs/xattr.c:1046
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81344ba0-ffffffff81344cca: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81350e90)
Location: fs/xattr.c:1078
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81350e90-ffffffff81350fba: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81357b80)
Location: fs/xattr.c:1107
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81357b80-ffffffff81357cb0: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a5fb0)
Location: fs/xattr.c:1108
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff813a5fb0-ffffffff813a60e0: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8142a340)
Location: fs/xattr.c:1160
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff8142a340-ffffffff8142a47f: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b7490)
Location: fs/xattr.c:1305
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff814b7490-ffffffff814b75de: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814ec2f0)
Location: fs/xattr.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff814ec2f0-ffffffff814ec424: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff815201d0)
Location: fs/xattr.c:1308
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff815201d0-ffffffff81520304: simple_xattr_list (STB_GLOBAL)
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
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bf7a8)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffff8000103bf7a8-ffff8000103bf940: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059c598)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
c059c598-c059c6f4: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004be140)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
c0000000004be140-c0000000004be398: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe000280106)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffe000280106-ffffffe000280236: simple_xattr_list (STB_GLOBAL)
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
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81303970)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81303970-ffffffff81303a9a: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f4590)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff812f4590-ffffffff812f46ba: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301760)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81301760-ffffffff8130188a: simple_xattr_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t simple_xattr_list(struct inode *inode, struct simple_xattrs *xattrs, char *buffer, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81312aa0)
Location: fs/xattr.c:967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_listxattr
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
**Symbols:**

```
ffffffff81312aa0-ffffffff81312bc8: simple_xattr_list (STB_GLOBAL)
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
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>xattrs, buffer, size</code> ➡️ <code>inode, xattrs, buffer, size</code>
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
