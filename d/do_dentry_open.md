# Function: <code>do_dentry_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120a080)
Location: fs/open.c:687
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff8120a080-ffffffff8120a385: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122fd50)
Location: fs/open.c:687
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff8122fd50-ffffffff8123004d: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812422f0)
Location: fs/open.c:704
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff812422f0-ffffffff812425f2: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d670)
Location: fs/open.c:700
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff8124d670-ffffffff8124d96b: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126f6d0)
Location: fs/open.c:700
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff8126f6d0-ffffffff8126f9d1: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *), const struct cred *cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295090)
Location: fs/open.c:742
Inline: False
Direct callers:
  - fs/open.c:vfs_open
```
**Symbols:**

```
ffffffff81295090-ffffffff81295388: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a9d80)
Location: fs/open.c:720
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812a9d80-ffffffff812aa11f: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c6530)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812c6530-ffffffff812c68c2: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7f40)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812d7f40-ffffffff812d82d3: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130dfc0)
Location: fs/open.c:769
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff8130dfc0-ffffffff8130e374: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a0e0)
Location: fs/open.c:764
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff8131a0e0-ffffffff8131a448: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813201c0)
Location: fs/open.c:772
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff813201c0-ffffffff81320528: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136d770)
Location: fs/open.c:769
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
ffffffff8136d770-ffffffff8136daee: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eb880)
Location: fs/open.c:794
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
ffffffff813eb880-ffffffff813ebbf5: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473c30)
Location: fs/open.c:826
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
ffffffff81473c30-ffffffff81474056: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8420)
Location: fs/open.c:858
Inline: False
Direct callers:
  - fs/open.c:backing_file_open
  - fs/open.c:kernel_file_open
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
ffffffff814a8420-ffffffff814a8949: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9500)
Location: fs/open.c:902
Inline: False
Direct callers:
  - fs/open.c:kernel_file_open
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
ffffffff814d9500-ffffffff814d9a69: do_dentry_open (STB_LOCAL)
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
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037dab0)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffff80001037dab0-ffff80001037de64: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567534)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
c0567534-c0567940: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004728c0)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
  - fs/open.c:dentry_open
  - fs/open.c:finish_open
```
**Symbols:**

```
c0000000004728c0-c000000000472d70: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253756)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffe000253756-ffffffe000253a06: do_dentry_open (STB_LOCAL)
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
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d0520)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812d0520-ffffffff812d08b3: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c11a0)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812c11a0-ffffffff812c1533: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce330)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812ce330-ffffffff812ce6c3: do_dentry_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_dentry_open(struct file *f, struct inode *inode, int (*open)(struct inode *, struct file *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812df140)
Location: fs/open.c:740
Inline: False
Direct callers:
  - fs/open.c:open_with_fake_path
```
**Symbols:**

```
ffffffff812df140-ffffffff812df4d3: do_dentry_open (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct cred *cred</code>
</li>
</ul>
</details>
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
