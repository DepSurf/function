# Function: <code>ext4_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129a970)
Location: fs/ext4/inode.c:4885
Inline: False
```
**Symbols:**

```
ffffffff8129a970-ffffffff8129a9f3: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c8860)
Location: fs/ext4/inode.c:5226
Inline: False
```
**Symbols:**

```
ffffffff812c8860-ffffffff812c88e8: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812de430)
Location: fs/ext4/inode.c:5370
Inline: False
```
**Symbols:**

```
ffffffff812de430-ffffffff812de4b8: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813024a0)
Location: fs/ext4/inode.c:5495
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813024a0-ffffffff81302527: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81326e30)
Location: fs/ext4/inode.c:5548
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff81326e30-ffffffff81326eb7: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81355260)
Location: fs/ext4/inode.c:5644
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff81355260-ffffffff813552e7: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136d590)
Location: fs/ext4/inode.c:5696
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff8136d590-ffffffff8136d617: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396b90)
Location: fs/ext4/inode.c:5718
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff81396b90-ffffffff81396c17: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813af5c0)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813af5c0-ffffffff813af647: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fb640)
Location: fs/ext4/inode.c:5449
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813fb640-ffffffff813fb6dd: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140dda0)
Location: fs/ext4/inode.c:5540
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff8140dda0-ffffffff8140de3d: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81413f60)
Location: fs/ext4/inode.c:5536
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff81413f60-ffffffff81413ffd: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814672b0)
Location: fs/ext4/inode.c:5475
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff814672b0-ffffffff8146734d: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e6e80)
Location: fs/ext4/inode.c:5553
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff814e6e80-ffffffff814e6f2c: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580750)
Location: fs/ext4/inode.c:5671
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff81580750-ffffffff815808b6: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b7d10)
Location: fs/ext4/inode.c:5483
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff815b7d10-ffffffff815b7e70: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f0a90)
Location: fs/ext4/inode.c:5503
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/symlink.c:ext4_encrypted_symlink_getattr
```
**Symbols:**

```
ffffffff815f0a90-ffffffff815f0c04: ext4_getattr (STB_GLOBAL)
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
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010483ef0)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffff800010483ef0-ffff800010483fbc: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0645558)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
c0645558-c0645618: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a9060)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
c0000000005a9060-c0000000005a9140: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030c494)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffe00030c494-ffffffe00030c54e: ext4_getattr (STB_GLOBAL)
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
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7ba0)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813a7ba0-ffffffff813a7c27: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398630)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff81398630-ffffffff813986b7: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5400)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813a5400-ffffffff813a5487: ext4_getattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b9b40)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_file_getattr
```
**Symbols:**

```
ffffffff813b9b40-ffffffff813b9bc7: ext4_getattr (STB_GLOBAL)
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
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt, dentry, stat</code> ➡️ <code>path, stat, request_mask, query_flags</code>
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
<code>path, stat, request_mask, query_flags</code> ➡️ <code>mnt_userns, path, stat, request_mask, query_flags</code>
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
