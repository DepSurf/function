# Function: <code>kernfs_xattr_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cbca0)
Location: fs/kernfs/inode.c:307
Inline: False
```
**Symbols:**

```
ffffffff812cbca0-ffffffff812cbcff: kernfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d90f0)
Location: fs/kernfs/inode.c:307
Inline: False
```
**Symbols:**

```
ffffffff812d90f0-ffffffff812d914f: kernfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fd950)
Location: fs/kernfs/inode.c:308
Inline: False
```
**Symbols:**

```
ffffffff812fd950-ffffffff812fd9af: kernfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b480)
Location: fs/kernfs/inode.c:308
Inline: False
```
**Symbols:**

```
ffffffff8132b480-ffffffff8132b4df: kernfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_xattr_get(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81342640)
Location: fs/kernfs/inode.c:308
Inline: False
```
**Symbols:**

```
ffffffff81342640-ffffffff8134269f: kernfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136ace0)
Location: fs/kernfs/inode.c:290
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8136ace0-ffffffff8136ad29: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382ea0)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81382ea0-ffffffff81382ee9: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd612)
Location: fs/kernfs/inode.c:291
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813cd860-ffffffff813cd8bf: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df242)
Location: fs/kernfs/inode.c:291
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813df490-ffffffff813df4ef: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5e02)
Location: fs/kernfs/inode.c:294
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813e6130-ffffffff813e618f: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437a02)
Location: fs/kernfs/inode.c:294
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81437d30-ffffffff81437d8f: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2722)
Location: fs/kernfs/inode.c:300
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff814b2a90-ffffffff814b2afb: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815492c2)
Location: fs/kernfs/inode.c:296
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81549690-ffffffff815496fb: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580ea2)
Location: fs/kernfs/inode.c:296
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81581270-ffffffff815812db: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9952)
Location: fs/kernfs/inode.c:295
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff815b9d00-ffffffff815b9d6b: kernfs_xattr_get (STB_GLOBAL)
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
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff8000104513b0)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffff8000104513b0-ffff800010451414: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c06143a0)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
c06143a0-c06143f0: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569a90)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
c000000000569a90-c000000000569b14: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e4252)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffe0002e4252-ffffffe0002e42ac: kernfs_xattr_get (STB_GLOBAL)
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
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b480)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8137b480-ffffffff8137b4c9: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136bf50)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8136bf50-ffffffff8136bf99: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378f50)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81378f50-ffffffff81378f99: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_xattr_get(struct kernfs_node *kn, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138ca00)
Location: fs/kernfs/inode.c:289
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_get
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8138ca00-ffffffff8138ca49: kernfs_xattr_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kernfs_node *kn</code>
</li>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct xattr_handler *handler</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *unused</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *suffix</code>
</li>
<li>
<b>Param reordered. </b>
<code>handler, unused, inode, suffix, value, size</code> ➡️ <code>kn, name, value, size</code>
</li>
</ul>
</details>
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
