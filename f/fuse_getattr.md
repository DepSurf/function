# Function: <code>fuse_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_getattr(struct vfsmount *mnt, struct dentry *entry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813143e0)
Location: fs/fuse/dir.c:1710
Inline: False
```
**Symbols:**

```
ffffffff813143e0-ffffffff81314422: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_getattr(struct vfsmount *mnt, struct dentry *entry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348a40)
Location: fs/fuse/dir.c:1717
Inline: False
```
**Symbols:**

```
ffffffff81348a40-ffffffff81348a82: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_getattr(struct vfsmount *mnt, struct dentry *entry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135e290)
Location: fs/fuse/dir.c:1780
Inline: False
```
**Symbols:**

```
ffffffff8135e290-ffffffff8135e2d2: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81372d80)
Location: fs/fuse/dir.c:1780
Inline: False
```
**Symbols:**

```
ffffffff81372d80-ffffffff81372dc6: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81397a40)
Location: fs/fuse/dir.c:1777
Inline: False
```
**Symbols:**

```
ffffffff81397a40-ffffffff81397add: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c6ca0)
Location: fs/fuse/dir.c:1798
Inline: False
```
**Symbols:**

```
ffffffff813c6ca0-ffffffff813c6d59: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813dfe70)
Location: fs/fuse/dir.c:1630
Inline: False
```
**Symbols:**

```
ffffffff813dfe70-ffffffff813dff43: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140ba70)
Location: fs/fuse/dir.c:1616
Inline: False
```
**Symbols:**

```
ffffffff8140ba70-ffffffff8140bb3c: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81425520)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81425520-ffffffff814255ec: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81473780)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81473780-ffffffff814738c8: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f620)
Location: fs/fuse/dir.c:1821
Inline: False
```
**Symbols:**

```
ffffffff8148f620-ffffffff8148f735: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81495040)
Location: fs/fuse/dir.c:1841
Inline: False
```
**Symbols:**

```
ffffffff81495040-ffffffff8149515c: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ecad0)
Location: fs/fuse/dir.c:1790
Inline: False
```
**Symbols:**

```
ffffffff814ecad0-ffffffff814ecbec: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b840)
Location: fs/fuse/dir.c:1871
Inline: False
```
**Symbols:**

```
ffffffff8157b840-ffffffff8157b98e: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81621200)
Location: fs/fuse/dir.c:1904
Inline: False
```
**Symbols:**

```
ffffffff81621200-ffffffff8162134e: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81659650)
Location: fs/fuse/dir.c:1970
Inline: False
```
**Symbols:**

```
ffffffff81659650-ffffffff8165979e: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81693340)
Location: fs/fuse/dir.c:2071
Inline: False
```
**Symbols:**

```
ffffffff81693340-ffffffff81693404: fuse_getattr (STB_LOCAL)
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
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010508cc8)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffff800010508cc8-ffff800010508da4: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c4c4c)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
c06c4c4c-c06c4cb4: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064e790)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
c00000000064e790-c00000000064e8c8: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000374846)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffe000374846-ffffffe000374902: fuse_getattr (STB_LOCAL)
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
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141db00)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff8141db00-ffffffff8141dbcc: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140e580)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff8140e580-ffffffff8140e64c: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81419ca0)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81419ca0-ffffffff81419d6c: fuse_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81430a10)
Location: fs/fuse/dir.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81430a10-ffffffff81430adc: fuse_getattr (STB_LOCAL)
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
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt, entry, stat</code> ➡️ <code>path, stat, request_mask, flags</code>
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
<code>path, stat, request_mask, flags</code> ➡️ <code>mnt_userns, path, stat, request_mask, flags</code>
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
