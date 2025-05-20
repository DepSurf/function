# Function: <code>fuse_getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct dentry *entry, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311810)
Location: fs/fuse/dir.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81311810-ffffffff81311960: fuse_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct dentry *entry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81345c80)
Location: fs/fuse/dir.c:1779
Inline: False
```
**Symbols:**

```
ffffffff81345c80-ffffffff81345e2c: fuse_getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81367770)
Location: fs/fuse/xattr.c:64
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81367770-ffffffff81367933: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8137bda0)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8137bda0-ffffffff8137befe: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813a0c40)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813a0c40-ffffffff813a0d9e: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813d0020)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813d0020-ffffffff813d017d: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813e9590)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff813e9590-ffffffff813e96ed: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81415700)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81415700-ffffffff8141585b: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8142f530)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8142f530-ffffffff8142f695: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8147f3a0)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8147f3a0-ffffffff8147f503: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149aa10)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8149aa10-ffffffff8149ab75: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8149fc70)
Location: fs/fuse/xattr.c:52
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8149fc70-ffffffff8149fdc1: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff814f7c80)
Location: fs/fuse/xattr.c:52
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff814f7c80-ffffffff814f7dd1: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81587c90)
Location: fs/fuse/xattr.c:51
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81587c90-ffffffff81587dff: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8162dfd0)
Location: fs/fuse/xattr.c:51
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
```
**Symbols:**

```
ffffffff8162dfd0-ffffffff8162e13f: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81666200)
Location: fs/fuse/xattr.c:51
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
```
**Symbols:**

```
ffffffff81666200-ffffffff81666374: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff816a04e0)
Location: fs/fuse/xattr.c:51
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
```
**Symbols:**

```
ffffffff816a04e0-ffffffff816a0654: fuse_getxattr (STB_GLOBAL)
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
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffff800010513ed0)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffff800010513ed0-ffff800010514020: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c06ced60)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
c06ced60-c06ceeb0: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c00000000065c050)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
c00000000065c050-c00000000065c214: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffe00037db60)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffe00037db60-ffffffe00037dc9c: fuse_getxattr (STB_GLOBAL)
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
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81427b10)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81427b10-ffffffff81427c75: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81418590)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81418590-ffffffff814186f5: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81423cb0)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff81423cb0-ffffffff81423e15: fuse_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fuse_getxattr(struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8143aaf0)
Location: fs/fuse/xattr.c:49
Inline: False
Direct callers:
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/acl.c:fuse_get_acl
```
**Symbols:**

```
ffffffff8143aaf0-ffffffff8143ac55: fuse_getxattr (STB_GLOBAL)
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
<code>entry, name, value, size</code> ➡️ <code>entry, inode, name, value, size</code>
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
<code>struct dentry *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, inode, name, value, size</code> ➡️ <code>inode, name, value, size</code>
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
