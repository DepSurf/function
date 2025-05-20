# Function: <code>fuse_invalidate_entry_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81311f77)
Location: fs/fuse/dir.c:133
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81312dc0-ffffffff81312dd3: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348780)
Location: fs/fuse/dir.c:135
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81347340-ffffffff81347353: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135ed2b)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8135cc50-ffffffff8135cc66: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813738f7)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81371640-ffffffff81371656: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81398603)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81396340-ffffffff81396356: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c77f6)
Location: fs/fuse/dir.c:127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff813c64c0-ffffffff813c64d6: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813e0a06)
Location: fs/fuse/dir.c:122
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff813df690-ffffffff813df6a6: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140c5d6)
Location: fs/fuse/dir.c:122
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8140b2c0-ffffffff8140b2d6: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142614e)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81423c50-ffffffff81423c62: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8147563c)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81473140-ffffffff81473152: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814902f7)
Location: fs/fuse/dir.c:157
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8148db10-ffffffff8148db22: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81495d27)
Location: fs/fuse/dir.c:157
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff814933b0-ffffffff81493420: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ed7e7)
Location: fs/fuse/dir.c:157
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff814ea810-ffffffff814ea880: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157c684)
Location: fs/fuse/dir.c:160
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff815792f0-ffffffff81579387: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816220a4)
Location: fs/fuse/dir.c:166
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8161e950-ffffffff8161e9e7: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8165a4fd)
Location: fs/fuse/dir.c:166
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81656d90-ffffffff81656e27: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816941cd)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff816909e0-ffffffff81690a7d: fuse_invalidate_entry_cache (STB_GLOBAL)
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
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010509970)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffff8000105073b8-ffff8000105073e8: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c5920)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
c06c3304-c06c3328: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064f7f4)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
c00000000064c910-c00000000064c928: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe0003753b4)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffe000373310-ffffffe00037333c: fuse_invalidate_entry_cache (STB_GLOBAL)
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
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141e72e)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8141c230-ffffffff8141c242: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140f1ae)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8140ccb0-ffffffff8140ccc2: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141a8ce)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff814183d0-ffffffff814183e2: fuse_invalidate_entry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_invalidate_entry_cache(struct dentry *entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8143166e)
Location: fs/fuse/dir.c:156
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_lookup
Direct callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8142f150-ffffffff8142f162: fuse_invalidate_entry_cache (STB_GLOBAL)
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
