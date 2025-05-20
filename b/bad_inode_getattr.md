# Function: <code>bad_inode_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812299a0)
Location: fs/bad_inode.c:92
Inline: True
```
**Symbols:**

```
ffffffff812299a0-ffffffff812299b0: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812520f0)
Location: fs/bad_inode.c:92
Inline: True
```
**Symbols:**

```
ffffffff812520f0-ffffffff81252100: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812652f0)
Location: fs/bad_inode.c:92
Inline: True
```
**Symbols:**

```
ffffffff812652f0-ffffffff81265300: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81272b30)
Location: fs/bad_inode.c:92
Inline: False
```
**Symbols:**

```
ffffffff81272b30-ffffffff81272b40: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81295460)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff81295460-ffffffff81295470: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812bb670)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812bb670-ffffffff812bb680: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812d0860)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812d0860-ffffffff812d0870: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed8c0)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812ed8c0-ffffffff812ed8d0: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff380)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812ff380-ffffffff812ff390: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81338440)
Location: fs/bad_inode.c:94
Inline: False
```
**Symbols:**

```
ffffffff81338440-ffffffff81338450: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81343dd0)
Location: fs/bad_inode.c:94
Inline: False
```
**Symbols:**

```
ffffffff81343dd0-ffffffff81343de0: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bad_inode_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8134a170)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff8134a170-ffffffff8134a180: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bad_inode_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81397ed0)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff81397ed0-ffffffff81397ee0: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bad_inode_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8141a430)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff8141a430-ffffffff8141a444: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bad_inode_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814a6220)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff814a6220-ffffffff814a6234: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bad_inode_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814db1e0)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff814db1e0-ffffffff814db1f4: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bad_inode_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8150d7a0)
Location: fs/bad_inode.c:98
Inline: False
```
**Symbols:**

```
ffffffff8150d7a0-ffffffff8150d7b4: bad_inode_getattr (STB_LOCAL)
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
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffff8000103b07f0)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffff8000103b07f0-ffff8000103b080c: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c05900f8)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
c05900f8-c0590114: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac1b0)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
c0000000004ac1b0-c0000000004ac1c0: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffe000274b6a)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffe000274b6a-ffffffe000274b86: bad_inode_getattr (STB_LOCAL)
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
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f7960)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812f7960-ffffffff812f7970: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e8580)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812e8580-ffffffff812e8590: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f5770)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff812f5770-ffffffff812f5780: bad_inode_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bad_inode_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81306900)
Location: fs/bad_inode.c:93
Inline: False
```
**Symbols:**

```
ffffffff81306900-ffffffff81306910: bad_inode_getattr (STB_LOCAL)
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
