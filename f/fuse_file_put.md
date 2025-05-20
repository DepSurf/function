# Function: <code>fuse_file_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81315730)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_common
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81315730-ffffffff813157c6: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81349f80)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81349f80-ffffffff8134a00b: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8135f8c0)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8135f8c0-ffffffff8135f952: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813743a0)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff813743a0-ffffffff8137443e: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81399120)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81399120-ffffffff813991c2: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c7e70)
Location: fs/fuse/file.c:89
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff813c7e70-ffffffff813c7f12: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e10c0)
Location: fs/fuse/file.c:92
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff813e10c0-ffffffff813e115b: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140ccc0)
Location: fs/fuse/file.c:88
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8140ccc0-ffffffff8140cd79: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814267d0)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff814267d0-ffffffff81426887: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81476810)
Location: fs/fuse/file.c:112
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81476810-ffffffff814768d9: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491550)
Location: fs/fuse/file.c:118
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81491550-ffffffff8149161f: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496750)
Location: fs/fuse/file.c:106
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff81496750-ffffffff8149681f: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ee030)
Location: fs/fuse/file.c:106
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff814ee030-ffffffff814ee0ff: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157d7c0)
Location: fs/fuse/file.c:106
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff8157d7c0-ffffffff8157d8ad: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623330)
Location: fs/fuse/file.c:106
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff81623330-ffffffff8162341d: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165b710)
Location: fs/fuse/file.c:107
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff8165b710-ffffffff8165b7fd: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816953f0)
Location: fs/fuse/file.c:108
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_file_release
```
**Symbols:**

```
ffffffff816953f0-ffffffff816954dd: fuse_file_put (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050a3d8)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffff80001050a3d8-ffff80001050a4a4: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c6434)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
c06c6434-c06c64e8: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006505f0)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
c0000000006505f0-c000000000650728: fuse_file_put (STB_LOCAL)
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
In fs/fuse/file.c (ffffffe00037a57c)
Location: fs/fuse/file.c:111
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_common
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffe000375a16-ffffffe000375acc: fuse_file_put.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141edb0)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8141edb0-ffffffff8141ee67: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140f830)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8140f830-ffffffff8140f8e7: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141af50)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff8141af50-ffffffff8141b007: fuse_file_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_file_put(struct fuse_file *ff, bool sync, bool isdir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81432140)
Location: fs/fuse/file.c:111
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_sync_release
  - fs/fuse/file.c:fuse_release_common
```
**Symbols:**

```
ffffffff81432140-ffffffff814321f7: fuse_file_put (STB_LOCAL)
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
<b>Param added. </b>
<code>bool isdir</code>
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
