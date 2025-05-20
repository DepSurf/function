# Function: <code>fuse_rename_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81312a70)
Location: fs/fuse/dir.c:700
Inline: False
```
**Symbols:**

```
ffffffff81312a70-ffffffff81312cde: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81347000)
Location: fs/fuse/dir.c:704
Inline: False
```
**Symbols:**

```
ffffffff81347000-ffffffff8134726e: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135c130)
Location: fs/fuse/dir.c:717
Inline: False
```
**Symbols:**

```
ffffffff8135c130-ffffffff8135c3a9: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81370ad0)
Location: fs/fuse/dir.c:717
Inline: False
```
**Symbols:**

```
ffffffff81370ad0-ffffffff81370d67: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813957d0)
Location: fs/fuse/dir.c:717
Inline: False
```
**Symbols:**

```
ffffffff813957d0-ffffffff81395a67: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c49d0)
Location: fs/fuse/dir.c:718
Inline: False
```
**Symbols:**

```
ffffffff813c49d0-ffffffff813c4c57: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de0b0)
Location: fs/fuse/dir.c:715
Inline: False
```
**Symbols:**

```
ffffffff813de0b0-ffffffff813de356: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:702
Inline: False
```
**Symbols:**

```
ffffffff8140a030-ffffffff8140a2ac: fuse_rename_common (STB_LOCAL)
ffffffff8140c6d3-ffffffff8140c6df: fuse_rename_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffff814236f0-ffffffff8142396d: fuse_rename_common (STB_LOCAL)
ffffffff81426263-ffffffff8142626f: fuse_rename_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81472c30)
Location: fs/fuse/dir.c:758
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff81472c30-ffffffff81472f38: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148d5e0)
Location: fs/fuse/dir.c:855
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff8148d5e0-ffffffff8148d8e8: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81492cb0)
Location: fs/fuse/dir.c:872
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff81492cb0-ffffffff81492fc9: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ec3f0)
Location: fs/fuse/dir.c:820
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff814ec3f0-ffffffff814ec721: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b220)
Location: fs/fuse/dir.c:929
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff8157b220-ffffffff8157b478: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81620a10)
Location: fs/fuse/dir.c:952
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff81620a10-ffffffff81620cd9: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81658e60)
Location: fs/fuse/dir.c:1018
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff81658e60-ffffffff81659124: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81692b90)
Location: fs/fuse/dir.c:1015
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rename2
```
**Symbols:**

```
ffffffff81692b90-ffffffff81692e76: fuse_rename_common (STB_LOCAL)
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
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010506ee0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffff800010506ee0-ffff800010507180: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c2e44)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
c06c2e44-c06c3154: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064c1b0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
c00000000064c1b0-c00000000064c4e0: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000372dbe)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffe000372dbe-ffffffe000372ff4: fuse_rename_common (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffff8141bcd0-ffffffff8141bf4d: fuse_rename_common (STB_LOCAL)
ffffffff8141e843-ffffffff8141e84f: fuse_rename_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffff8140c750-ffffffff8140c9cd: fuse_rename_common (STB_LOCAL)
ffffffff8140f2c3-ffffffff8140f2cf: fuse_rename_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffff81417e70-ffffffff814180ed: fuse_rename_common (STB_LOCAL)
ffffffff8141a9e3-ffffffff8141a9ef: fuse_rename_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fuse_rename_common(struct inode *olddir, struct dentry *oldent, struct inode *newdir, struct dentry *newent, unsigned int flags, int opcode, size_t argsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:758
Inline: False
```
**Symbols:**

```
ffffffff8142ebf0-ffffffff8142ee6d: fuse_rename_common (STB_LOCAL)
ffffffff81431783-ffffffff8143178f: fuse_rename_common.cold (STB_LOCAL)
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
