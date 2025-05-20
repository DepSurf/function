# Function: <code>kernfs_xattr_set</code>

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
int kernfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cbd00)
Location: fs/kernfs/inode.c:322
Inline: False
```
**Symbols:**

```
ffffffff812cbd00-ffffffff812cbd63: kernfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d9150)
Location: fs/kernfs/inode.c:322
Inline: False
```
**Symbols:**

```
ffffffff812d9150-ffffffff812d91b3: kernfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fd9b0)
Location: fs/kernfs/inode.c:323
Inline: False
```
**Symbols:**

```
ffffffff812fd9b0-ffffffff812fda13: kernfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b4e0)
Location: fs/kernfs/inode.c:323
Inline: False
```
**Symbols:**

```
ffffffff8132b4e0-ffffffff8132b543: kernfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_xattr_set(const struct xattr_handler *handler, struct dentry *unused, struct inode *inode, const char *suffix, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813426a0)
Location: fs/kernfs/inode.c:323
Inline: False
```
**Symbols:**

```
ffffffff813426a0-ffffffff81342703: kernfs_xattr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136ad70)
Location: fs/kernfs/inode.c:300
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8136ad70-ffffffff8136adc4: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382f30)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81382f30-ffffffff81382f84: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd5a0)
Location: fs/kernfs/inode.c:301
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813cd8c0-ffffffff813cd913: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df1d0)
Location: fs/kernfs/inode.c:301
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813df4f0-ffffffff813df543: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5d9b)
Location: fs/kernfs/inode.c:304
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff813e6190-ffffffff813e61e3: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8143791b)
Location: fs/kernfs/inode.c:304
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81437d90-ffffffff81437de3: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b26ab)
Location: fs/kernfs/inode.c:310
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff814b2b00-ffffffff814b2b65: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8154923b)
Location: fs/kernfs/inode.c:306
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81549710-ffffffff81549775: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580e1b)
Location: fs/kernfs/inode.c:306
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff815812f0-ffffffff81581355: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b98bb)
Location: fs/kernfs/inode.c:305
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff815b9d80-ffffffff815b9df1: kernfs_xattr_set (STB_GLOBAL)
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
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff800010451480)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffff800010451480-ffff8000104514f4: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0614424)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
c0614424-c0614484: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569b80)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
c000000000569b80-c000000000569c14: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e4302)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffe0002e4302-ffffffe0002e4362: kernfs_xattr_set (STB_GLOBAL)
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
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b510)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8137b510-ffffffff8137b564: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136bfe0)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8136bfe0-ffffffff8136c034: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378fe0)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff81378fe0-ffffffff81379034: kernfs_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_xattr_set(struct kernfs_node *kn, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138ca90)
Location: fs/kernfs/inode.c:299
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_vfs_xattr_set
  - security/selinux/hooks.c:selinux_kernfs_init_security
```
**Symbols:**

```
ffffffff8138ca90-ffffffff8138cae4: kernfs_xattr_set (STB_GLOBAL)
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
<code>handler, unused, inode, suffix, value, size, flags</code> ➡️ <code>kn, name, value, size, flags</code>
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
