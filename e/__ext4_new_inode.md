# Function: <code>__ext4_new_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81294230)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff81294230-ffffffff812955e2: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c17c0)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff812c17c0-ffffffff812c2c2f: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d6df0)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff812d6df0-ffffffff812d821a: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f50b0)
Location: fs/ext4/ialloc.c:743
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812f50b0-ffffffff812f65ae: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81319800)
Location: fs/ext4/ialloc.c:772
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81319800-ffffffff8131abdd: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813475b0)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813475b0-ffffffff81348b61: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8135f760)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8135f760-ffffffff81360d11: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81388910)
Location: fs/ext4/ialloc.c:742
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81388910-ffffffff81389e16: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a12c0)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813a12c0-ffffffff813a283e: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ed540)
Location: fs/ext4/ialloc.c:755
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
**Symbols:**

```
ffffffff813ed540-ffffffff813ee872: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ffce0)
Location: fs/ext4/ialloc.c:922
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
**Symbols:**

```
ffffffff813ffce0-ffffffff81400fdf: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(struct user_namespace *mnt_userns, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81406080)
Location: fs/ext4/ialloc.c:923
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81406080-ffffffff81407512: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_new_inode(struct user_namespace *mnt_userns, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:925
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81cca335-ffffffff81cca40a: __ext4_new_inode.cold (STB_LOCAL)
ffffffff814588e0-ffffffff81459dbb: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_new_inode(struct user_namespace *mnt_userns, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:925
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81e7d06a-ffffffff81e7d121: __ext4_new_inode.cold (STB_LOCAL)
ffffffff814d64b0-ffffffff814d7a5a: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_new_inode(struct user_namespace *mnt_userns, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:924
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
**Symbols:**

```
ffffffff8206d635-ffffffff8206d6de: __ext4_new_inode.cold (STB_LOCAL)
ffffffff8156f280-ffffffff815707bf: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_new_inode(struct mnt_idmap *idmap, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:923
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
**Symbols:**

```
ffffffff820ed33b-ffffffff820ed39b: __ext4_new_inode.cold (STB_LOCAL)
ffffffff815a70b0-ffffffff815a85af: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *__ext4_new_inode(struct mnt_idmap *idmap, handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:923
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
**Symbols:**

```
ffffffff821ca481-ffffffff821ca4db: __ext4_new_inode.cold (STB_LOCAL)
ffffffff815dff30-ffffffff815e135f: __ext4_new_inode (STB_GLOBAL)
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
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010474b50)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffff800010474b50-ffff800010475e64: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0636114)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0636114-c06378ac: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0000000005962c0)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0000000005962c0-c000000000597c8c: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe00030057e)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffe00030057e-ffffffe000301836: __ext4_new_inode (STB_GLOBAL)
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
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813998a0)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813998a0-ffffffff8139ae1e: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8138a330)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8138a330-ffffffff8138b8ae: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81397100)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81397100-ffffffff8139867e: __ext4_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *__ext4_new_inode(handle_t *handle, struct inode *dir, umode_t mode, const struct qstr *qstr, __u32 goal, uid_t *owner, __u32 i_flags, int handle_type, unsigned int line_no, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ab420)
Location: fs/ext4/ialloc.c:740
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813ab420-ffffffff813aca95: __ext4_new_inode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u32 i_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, mode, qstr, goal, owner, handle_type, line_no, nblocks</code> ➡️ <code>handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code>
</li>
</ul>
</details>
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
<code>handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code> ➡️ <code>mnt_userns, handle, dir, mode, qstr, goal, owner, i_flags, handle_type, line_no, nblocks</code>
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
