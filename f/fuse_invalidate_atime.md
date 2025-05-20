# Function: <code>fuse_invalidate_atime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311aed)
Location: fs/fuse/dir.c:119
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_follow_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81312da0-ffffffff81312dc0: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81345fe4)
Location: fs/fuse/dir.c:121
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81347320-ffffffff81347340: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135b9b4)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff8135cc30-ffffffff8135cc50: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8137033c)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81371620-ffffffff81371640: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8139503c)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff81396320-ffffffff81396340: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c426f)
Location: fs/fuse/dir.c:113
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
```
**Symbols:**

```
ffffffff813c64a0-ffffffff813c64c0: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff813dddb9)
Location: fs/fuse/dir.c:108
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:__fuse_direct_read
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813ddca0-ffffffff813ddcc7: fuse_invalidate_atime.part.20 (STB_LOCAL)
ffffffff813df670-ffffffff813df68b: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81409da8)
Location: fs/fuse/dir.c:108
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81409c90-ffffffff81409cb7: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff8140b2a0-ffffffff8140b2bb: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142339e)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814232b0-ffffffff814232d7: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff81423c30-ffffffff81423c4b: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814728f7)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81473100-ffffffff81473133: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148d297)
Location: fs/fuse/dir.c:143
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8148dad0-ffffffff8148db03: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81492997)
Location: fs/fuse/dir.c:143
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81493370-ffffffff814933a3: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ea377)
Location: fs/fuse/dir.c:143
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814ea7d0-ffffffff814ea803: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81578f46)
Location: fs/fuse/dir.c:146
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff815792a0-ffffffff815792ef: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161e556)
Location: fs/fuse/dir.c:152
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8161e8f0-ffffffff8161e933: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8165697e)
Location: fs/fuse/dir.c:152
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81656d30-ffffffff81656d77: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816901fe)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81690980-ffffffff816909c7: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffff800010506840)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffff800010506738-ffff800010506798: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffff800010507380-ffff8000105073b8: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c28f0)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c06c32d4-c06c3304: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (c00000000064bbac)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c00000000064ba70-c00000000064bae4: fuse_invalidate_atime.part.0 (STB_LOCAL)
c00000000064c8e0-c00000000064c904: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffe000372a2e)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe000372962-ffffffe0003729a8: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffe0003732de-ffffffe000373310: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141b97e)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8141b890-ffffffff8141b8b7: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff8141c210-ffffffff8141c22b: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140c3fe)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8140c310-ffffffff8140c337: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff8140cc90-ffffffff8140ccab: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff81417b1e)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81417a30-ffffffff81417a57: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff814183b0-ffffffff814183cb: fuse_invalidate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_invalidate_atime(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142e90e)
Location: fs/fuse/dir.c:142
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readlink_page
Direct callers:
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8142e820-ffffffff8142e847: fuse_invalidate_atime.part.0 (STB_LOCAL)
ffffffff8142f130-ffffffff8142f14b: fuse_invalidate_atime (STB_GLOBAL)
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
