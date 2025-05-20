# Function: <code>anon_inode_getfd_secure</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int anon_inode_getfd_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81383ee0)
Location: fs/anon_inodes.c:220
Inline: False
Direct callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff81383ee0-ffffffff81383f5e: anon_inode_getfd_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int anon_inode_getfd_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff813d1180)
Location: fs/anon_inodes.c:220
Inline: False
Direct callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff813d1180-ffffffff813d11fe: anon_inode_getfd_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int anon_inode_getfd_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8145a3c0)
Location: fs/anon_inodes.c:249
Inline: False
Direct callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff8145a3c0-ffffffff8145a44a: anon_inode_getfd_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int anon_inode_getfd_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff814e98b0)
Location: fs/anon_inodes.c:249
Inline: False
Direct callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff814e98b0-ffffffff814e993a: anon_inode_getfd_secure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int anon_inode_getfd_secure(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81520650)
Location: fs/anon_inodes.c:249
Inline: False
Direct callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff81520650-ffffffff815206da: anon_inode_getfd_secure (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
