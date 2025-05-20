# Function: <code>do_getxattr</code>

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
ssize_t do_getxattr(struct user_namespace *mnt_userns, struct dentry *d, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429a80)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_fgetxattr
```
**Symbols:**

```
ffffffff81429a80-ffffffff81429c06: do_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_getxattr(struct mnt_idmap *idmap, struct dentry *d, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6ac0)
Location: fs/xattr.c:724
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
**Symbols:**

```
ffffffff814b6ac0-ffffffff814b6c4c: do_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_getxattr(struct mnt_idmap *idmap, struct dentry *d, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb7d0)
Location: fs/xattr.c:722
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
**Symbols:**

```
ffffffff814eb7d0-ffffffff814eb954: do_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_getxattr(struct mnt_idmap *idmap, struct dentry *d, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f670)
Location: fs/xattr.c:722
Inline: False
Direct callers:
  - fs/xattr.c:getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
**Symbols:**

```
ffffffff8151f670-ffffffff8151f7f4: do_getxattr (STB_GLOBAL)
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
