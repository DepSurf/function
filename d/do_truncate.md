# Function: <code>do_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812094c0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812094c0-ffffffff8120957a: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f2b0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8122f2b0-ffffffff8122f366: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241800)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81241800-ffffffff812418b6: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124cb60)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8124cb60-ffffffff8124cc16: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126ead0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8126ead0-ffffffff8126eb86: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812946c0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812946c0-ffffffff8129477c: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a93e0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:path_openat
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812a93e0-ffffffff812a949c: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c5b30)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c5b30-ffffffff812c5bf4: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7540)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812d7540-ffffffff812d7604: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130d630)
Location: fs/open.c:38
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:handle_truncate
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8130d630-ffffffff8130d6f4: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319590)
Location: fs/open.c:38
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:handle_truncate
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81319590-ffffffff81319654: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_truncate(struct user_namespace *mnt_userns, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81320b90)
Location: fs/open.c:38
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81320b90-ffffffff81320c5e: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_truncate(struct user_namespace *mnt_userns, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136cc30)
Location: fs/open.c:38
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8136cc30-ffffffff8136ccfe: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_truncate(struct user_namespace *mnt_userns, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ec790)
Location: fs/open.c:39
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813ec790-ffffffff813ec87c: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_truncate(struct user_namespace *mnt_userns, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474cc0)
Location: fs/open.c:39
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81474cc0-ffffffff81474daf: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_truncate(struct mnt_idmap *idmap, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a9650)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814a9650-ffffffff814a973f: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_truncate(struct mnt_idmap *idmap, struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814da6b0)
Location: fs/open.c:40
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_open
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814da6b0-ffffffff814da79f: do_truncate (STB_GLOBAL)
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
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037c8c8)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff80001037c8c8-ffff80001037c9b8: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567318)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c0567318-c05673fc: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000471b10)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000471b10-c000000000471c4c: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000252f5c)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe000252f5c-ffffffe000253008: do_truncate (STB_GLOBAL)
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
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfb20)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812cfb20-ffffffff812cfbe4: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c07a0)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812c07a0-ffffffff812c0864: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cd930)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812cd930-ffffffff812cd9f4: do_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_truncate(struct dentry *dentry, loff_t length, unsigned int time_attrs, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812de740)
Location: fs/open.c:41
Inline: False
Direct callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/namei.c:do_last
  - fs/coredump.c:dump_truncate
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff812de740-ffffffff812de804: do_truncate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, length, time_attrs, filp</code> ➡️ <code>mnt_userns, dentry, length, time_attrs, filp</code>
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
