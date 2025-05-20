# Function: <code>fat_truncate_time</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813c96f0)
Location: fs/fat/misc.c:284
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813c96f0-ffffffff813c9856: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f4290)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813f4290-ffffffff813f43f6: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140e160)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8140e160-ffffffff8140e2c6: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8145bf30)
Location: fs/fat/misc.c:293
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8145bf30-ffffffff8145c09a: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81477e30)
Location: fs/fat/misc.c:293
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81477e30-ffffffff81477f9a: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8147d8a0)
Location: fs/fat/misc.c:293
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8147d8a0-ffffffff8147da0b: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814d5120)
Location: fs/fat/misc.c:296
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff814d5120-ffffffff814d528b: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81562150)
Location: fs/fat/misc.c:314
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81562150-ffffffff8156228a: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff816048c0)
Location: fs/fat/misc.c:314
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff816048c0-ffffffff816049fa: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163c7d0)
Location: fs/fat/misc.c:314
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8163c7d0-ffffffff8163c90a: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81675d60)
Location: fs/fat/misc.c:314
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_write_end
  - fs/fat/misc.c:fat_update_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81675d60-ffffffff81675e93: fat_truncate_time (STB_GLOBAL)
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
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104eec98)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffff8000104eec98-ffff8000104eede4: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06ac774)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c06ac774-c06ac928: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062dd40)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c00000000062dd40-c00000000062df4c: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035edd6)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffe00035edd6-ffffffe00035eed6: fat_truncate_time (STB_GLOBAL)
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
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81406740)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81406740-ffffffff814068a6: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f71c0)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813f71c0-ffffffff813f7326: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81403ac0)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81403ac0-ffffffff81403c26: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_truncate_time(struct inode *inode, struct timespec64 *now, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81419730)
Location: fs/fat/misc.c:285
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81419730-ffffffff81419896: fat_truncate_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
