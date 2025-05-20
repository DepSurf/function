# Function: <code>fuse_sync_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81315210)
Location: fs/fuse/file.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81315210-ffffffff81315284: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81349a60)
Location: fs/fuse/file.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81349a60-ffffffff81349ad4: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8135f370)
Location: fs/fuse/file.c:299
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8135f370-ffffffff8135f3e4: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81374440)
Location: fs/fuse/file.c:294
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81374440-ffffffff81374476: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813991d0)
Location: fs/fuse/file.c:294
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff813991d0-ffffffff81399206: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c8c30)
Location: fs/fuse/file.c:294
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff813c8c30-ffffffff813c8c66: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1e70)
Location: fs/fuse/file.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff813e1e70-ffffffff813e1ea8: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:304
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81412992-ffffffff814129ab: fuse_sync_release.cold (STB_LOCAL)
ffffffff8140dd10-ffffffff8140dd5c: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81426e90)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81426e90-ffffffff81426eca: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477390)
Location: fs/fuse/file.c:325
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81477390-ffffffff814773cc: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492130)
Location: fs/fuse/file.c:348
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81492130-ffffffff8149216c: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814972f0)
Location: fs/fuse/file.c:351
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff814972f0-ffffffff8149732c: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814eec70)
Location: fs/fuse/file.c:354
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff814eec70-ffffffff814eecac: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157d8b0)
Location: fs/fuse/file.c:360
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8157d8b0-ffffffff8157d8f9: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623430)
Location: fs/fuse/file.c:360
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81623430-ffffffff81623479: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165b810)
Location: fs/fuse/file.c:361
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8165b810-ffffffff8165b859: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816954f0)
Location: fs/fuse/file.c:362
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff816954f0-ffffffff81695539: fuse_sync_release (STB_GLOBAL)
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
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050b5f8)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffff80001050b5f8-ffff80001050b664: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c64e8)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
c06c64e8-c06c6558: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000650730)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
c000000000650730-c000000000650790: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000376244)
Location: fs/fuse/file.c:324
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffe000376244-ffffffe0003762ae: fuse_sync_release (STB_GLOBAL)
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
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f470)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8141f470-ffffffff8141f4aa: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140fef0)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8140fef0-ffffffff8140ff2a: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141b610)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff8141b610-ffffffff8141b64a: fuse_sync_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_sync_release(struct fuse_inode *fi, struct fuse_file *ff, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81432200)
Location: fs/fuse/file.c:324
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
```
**Symbols:**

```
ffffffff81432200-ffffffff8143223a: fuse_sync_release (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_inode *fi</code>
</li>
<li>
<b>Param reordered. </b>
<code>ff, flags</code> ➡️ <code>fi, ff, flags</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>unsigned int flags</code>
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
