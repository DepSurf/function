# Function: <code>fuse_dev_do_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81310840)
Location: fs/fuse/dev.c:1241
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_read
  - fs/fuse/dev.c:fuse_dev_splice_read
```
**Symbols:**

```
ffffffff81310840-ffffffff81310e4b: fuse_dev_do_read.isra.21.constprop.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81344c10)
Location: fs/fuse/dev.c:1216
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81344c10-ffffffff8134525c: fuse_dev_do_read.isra.22.constprop.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135a9f0)
Location: fs/fuse/dev.c:1219
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8135a9f0-ffffffff8135b014: fuse_dev_do_read.isra.25.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136e5e0)
Location: fs/fuse/dev.c:1218
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8136e5e0-ffffffff8136ee2b: fuse_dev_do_read.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81393200)
Location: fs/fuse/dev.c:1218
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81393200-ffffffff81393a1f: fuse_dev_do_read.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c19e0)
Location: fs/fuse/dev.c:1231
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff813c19e0-ffffffff813c220b: fuse_dev_do_read.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff813db1a0)
Location: fs/fuse/dev.c:1284
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff813db1a0-ffffffff813dba12: fuse_dev_do_read.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81407620)
Location: fs/fuse/dev.c:1308
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81407620-ffffffff81407e2a: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81421030)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81421030-ffffffff814217ef: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81470140)
Location: fs/fuse/dev.c:1175
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81470140-ffffffff814709da: fuse_dev_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148aa40)
Location: fs/fuse/dev.c:1196
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8148aa40-ffffffff8148b2b4: fuse_dev_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81490c80)
Location: fs/fuse/dev.c:1193
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81490c80-ffffffff81491324: fuse_dev_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1209
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff814e8710-ffffffff814e8dd7: fuse_dev_do_read (STB_LOCAL)
ffffffff81cd2022-ffffffff81cd204a: fuse_dev_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1201
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81576570-ffffffff81576c2b: fuse_dev_do_read (STB_LOCAL)
ffffffff81e85144-ffffffff81e8516e: fuse_dev_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1202
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8161bd40-ffffffff8161c3fb: fuse_dev_do_read (STB_LOCAL)
ffffffff82072609-ffffffff82072633: fuse_dev_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1204
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81653eb0-ffffffff81654566: fuse_dev_do_read (STB_LOCAL)
ffffffff820f228d-ffffffff820f22b7: fuse_dev_do_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:1204
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8168e540-ffffffff8168ebf6: fuse_dev_do_read (STB_LOCAL)
ffffffff821cf56e-ffffffff821cf598: fuse_dev_do_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffff800010503d28)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffff800010503d28-ffff8000105045a8: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c03ac)
Location: fs/fuse/dev.c:1176
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
c06c03ac-c06c0ba4: fuse_dev_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_dev_do_read(struct fuse_dev *fud, struct file *file, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000648b40)
Location: fs/fuse/dev.c:1176
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
c000000000648b40-c0000000006495a8: fuse_dev_do_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffe0003709e8)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffe0003709e8-ffffffe0003711b4: fuse_dev_do_read.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81419610)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff81419610-ffffffff81419dcf: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140a090)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8140a090-ffffffff8140a84f: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff814157b0)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff814157b0-ffffffff81415f6f: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142c560)
Location: fs/fuse/dev.c:1176
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_dev_read
```
**Symbols:**

```
ffffffff8142c560-ffffffff8142cccf: fuse_dev_do_read.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
