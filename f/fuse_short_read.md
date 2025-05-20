# Function: <code>fuse_short_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81316540)
Location: fs/fuse/file.c:673
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81316540-ffffffff8131672b: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134ac70)
Location: fs/fuse/file.c:686
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8134ac70-ffffffff8134ae47: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81360580)
Location: fs/fuse/file.c:687
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81360580-ffffffff81360755: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813751d0)
Location: fs/fuse/file.c:682
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813751d0-ffffffff81375370: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81399e10)
Location: fs/fuse/file.c:682
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81399e10-ffffffff81399fa7: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c9530)
Location: fs/fuse/file.c:682
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813c9530-ffffffff813c96c8: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e21e0)
Location: fs/fuse/file.c:687
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff813e21e0-ffffffff813e2378: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_short_read(struct fuse_req *req, struct inode *inode, u64 attr_ver);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140dea0)
Location: fs/fuse/file.c:699
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8140dea0-ffffffff8140e040: fuse_short_read (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81427010)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffffffff81427010-ffffffff81427198: fuse_short_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814779a0)
Location: fs/fuse/file.c:773
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff814779a0-ffffffff81477b33: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814922f0)
Location: fs/fuse/file.c:796
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff814922f0-ffffffff814923ec: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81497330)
Location: fs/fuse/file.c:800
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff81497330-ffffffff814973ed: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814eecb0)
Location: fs/fuse/file.c:804
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff814eecb0-ffffffff814eed6d: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157d3a0)
Location: fs/fuse/file.c:813
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffff8157d3a0-ffffffff8157d475: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8162484c)
Location: fs/fuse/file.c:813
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165cc2c)
Location: fs/fuse/file.c:814
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81696986)
Location: fs/fuse/file.c:815
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_do_readpage
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
In fs/fuse/file.c (ffff80001050ba00)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffff80001050ba00-ffff80001050bbb4: fuse_short_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_short_read(struct inode *inode, u64 attr_ver, size_t num_read, struct fuse_args_pages *ap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6b44)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
c06c6b44-c06c6cc0: fuse_short_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (c000000000651420)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
c000000000651420-c000000000651628: fuse_short_read.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffe0003762ae)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_do_readpage
```
**Symbols:**

```
ffffffe0003762ae-ffffffe000376428: fuse_short_read.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8141f5f0)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffffffff8141f5f0-ffffffff8141f778: fuse_short_read.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81410070)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffffffff81410070-ffffffff814101f8: fuse_short_read.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8141b790)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffffffff8141b790-ffffffff8141b918: fuse_short_read.isra.0 (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff81432890)
Location: fs/fuse/file.c:756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
```
**Symbols:**

```
ffffffff81432890-ffffffff81432a37: fuse_short_read.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
