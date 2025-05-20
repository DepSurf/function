# Function: <code>fuse_do_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_do_setattr(struct inode *inode, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81314810)
Location: fs/fuse/dir.c:1589
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81314810-ffffffff81314d89: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_do_setattr(struct inode *inode, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348e70)
Location: fs/fuse/dir.c:1596
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81348e70-ffffffff81349403: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135e680)
Location: fs/fuse/dir.c:1612
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8135e680-ffffffff8135ec31: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81373190)
Location: fs/fuse/dir.c:1612
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81373190-ffffffff81373805: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81397ea0)
Location: fs/fuse/dir.c:1609
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81397ea0-ffffffff81398515: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c7120)
Location: fs/fuse/dir.c:1619
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff813c7120-ffffffff813c7724: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813e0310)
Location: fs/fuse/dir.c:1448
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff813e0310-ffffffff813e093e: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1434
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8140c6df-ffffffff8140c732: fuse_do_setattr.cold (STB_LOCAL)
ffffffff8140bf00-ffffffff8140c507: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814259b0)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff814259b0-ffffffff8142607d: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81475050)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81475050-ffffffff81475563: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148fb60)
Location: fs/fuse/dir.c:1593
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8148fb60-ffffffff814901e7: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81495590)
Location: fs/fuse/dir.c:1612
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81495590-ffffffff81495c1a: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ed020)
Location: fs/fuse/dir.c:1560
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff814ed020-ffffffff814ed6da: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157be50)
Location: fs/fuse/dir.c:1640
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8157be50-ffffffff8157c57e: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81621860)
Location: fs/fuse/dir.c:1673
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81621860-ffffffff81621f8c: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81659cb0)
Location: fs/fuse/dir.c:1739
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81659cb0-ffffffff8165a3e7: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81693920)
Location: fs/fuse/dir.c:1840
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81693920-ffffffff816940b7: fuse_do_setattr (STB_GLOBAL)
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
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010509240)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffff800010509240-ffff800010509888: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c515c)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
c06c515c-c06c5844: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064eeb0)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
c00000000064eeb0-c00000000064f698: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000374d0c)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffe000374d0c-ffffffe0003752de: fuse_do_setattr (STB_GLOBAL)
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
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141df90)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8141df90-ffffffff8141e65d: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140ea10)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8140ea10-ffffffff8140f0dd: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141a130)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff8141a130-ffffffff8141a7fd: fuse_do_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_do_setattr(struct dentry *dentry, struct iattr *attr, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81430e90)
Location: fs/fuse/dir.c:1490
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/file.c:fuse_do_truncate
```
**Symbols:**

```
ffffffff81430e90-ffffffff814315a0: fuse_do_setattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
</ul>
</details>
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
