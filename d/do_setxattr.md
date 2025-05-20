# Function: <code>do_setxattr</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_setxattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814294f0)
Location: fs/xattr.c:608
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814294f0-ffffffff8142958f: do_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_setxattr(struct mnt_idmap *idmap, struct dentry *dentry, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6470)
Location: fs/xattr.c:625
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814b6470-ffffffff814b653f: do_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_setxattr(struct mnt_idmap *idmap, struct dentry *dentry, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb180)
Location: fs/xattr.c:623
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff814eb180-ffffffff814eb241: do_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_setxattr(struct mnt_idmap *idmap, struct dentry *dentry, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f020)
Location: fs/xattr.c:623
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
```
**Symbols:**

```
ffffffff8151f020-ffffffff8151f0e1: do_setxattr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
