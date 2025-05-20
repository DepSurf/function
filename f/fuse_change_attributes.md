# Function: <code>fuse_change_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131bd50)
Location: fs/fuse/inode.c:204
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8131bd50-ffffffff8131be69: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81350840)
Location: fs/fuse/inode.c:202
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81350840-ffffffff81350950: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813661a0)
Location: fs/fuse/inode.c:204
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff813661a0-ffffffff813662b0: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137a860)
Location: fs/fuse/inode.c:204
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8137a860-ffffffff8137a96b: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139f700)
Location: fs/fuse/inode.c:204
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8139f700-ffffffff8139f80b: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cea90)
Location: fs/fuse/inode.c:204
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff813cea90-ffffffff813ceba6: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e7f00)
Location: fs/fuse/inode.c:203
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813e7f00-ffffffff813e8016: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81413fa0)
Location: fs/fuse/inode.c:200
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81413fa0-ffffffff814140d3: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142e040)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8142e040-ffffffff8142e173: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147dcb0)
Location: fs/fuse/inode.c:192
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8147dcb0-ffffffff8147dddd: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499030)
Location: fs/fuse/inode.c:219
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81499030-ffffffff81499161: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149e260)
Location: fs/fuse/inode.c:219
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8149e260-ffffffff8149e391: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6110)
Location: fs/fuse/inode.c:221
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff814f6110-ffffffff814f6241: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81585e70)
Location: fs/fuse/inode.c:238
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81585e70-ffffffff81586047: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162c0c0)
Location: fs/fuse/inode.c:238
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8162c0c0-ffffffff8162c2ad: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81664300)
Location: fs/fuse/inode.c:238
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81664300-ffffffff816644ed: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, struct fuse_statx *sx, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169e4f0)
Location: fs/fuse/inode.c:291
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff8169e4f0-ffffffff8169e6f4: fuse_change_attributes (STB_GLOBAL)
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
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff8000105126c0)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000105126c0-ffff800010512838: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cd7cc)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c06cd7cc-c06cd964: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c00000000065a370)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c00000000065a370-c00000000065a550: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c722)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00037c722-ffffffe00037c896: fuse_change_attributes (STB_GLOBAL)
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
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81426620)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81426620-ffffffff81426753: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814170a0)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff814170a0-ffffffff814171d3: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814227c0)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff814227c0-ffffffff814228f3: fuse_change_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_change_attributes(struct inode *inode, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814395f0)
Location: fs/fuse/inode.c:190
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff814395f0-ffffffff8143972a: fuse_change_attributes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_statx *sx</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, attr, attr_valid, attr_version</code> ➡️ <code>inode, attr, sx, attr_valid, attr_version</code>
</li>
</ul>
</details>
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
