# Function: <code>kernfs_get_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a590)
Location: fs/kernfs/dir.c:452
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_seq_start
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8128a590-ffffffff8128a5c0: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7a90)
Location: fs/kernfs/dir.c:451
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff812b79c0-ffffffff812b79f3: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd229)
Location: fs/kernfs/dir.c:401
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff812cd150-ffffffff812cd183: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da7ff)
Location: fs/kernfs/dir.c:411
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff812da4c0-ffffffff812da4ed: kernfs_get_active.part.13 (STB_LOCAL)
ffffffff812da750-ffffffff812da768: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff075)
Location: fs/kernfs/dir.c:412
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff812fed20-ffffffff812fed4d: kernfs_get_active.part.13 (STB_LOCAL)
ffffffff812fefb0-ffffffff812fefc8: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cd0b)
Location: fs/kernfs/dir.c:412
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8132c170-ffffffff8132c19d: kernfs_get_active.part.16 (STB_LOCAL)
ffffffff8132cc40-ffffffff8132cc58: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8134406e)
Location: fs/kernfs/dir.c:412
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff81343f80-ffffffff81343fc4: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c2c8)
Location: fs/kernfs/dir.c:411
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8136c1f0-ffffffff8136c220: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384478)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813843a0-ffffffff813843d0: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cee80)
Location: fs/kernfs/dir.c:413
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_file_direct_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813cee80-ffffffff813ceeb0: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0ab0)
Location: fs/kernfs/dir.c:413
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813e0ab0-ffffffff813e0ae0: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e75e0)
Location: fs/kernfs/dir.c:413
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813e75e0-ffffffff813e7610: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814392f0)
Location: fs/kernfs/dir.c:415
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff814392f0-ffffffff81439320: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4320)
Location: fs/kernfs/dir.c:422
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff814b4320-ffffffff814b435b: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b1b0)
Location: fs/kernfs/dir.c:433
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8154b1b0-ffffffff8154b1eb: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582e00)
Location: fs/kernfs/dir.c:430
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff81582e00-ffffffff81582e3b: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bba30)
Location: fs/kernfs/dir.c:434
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_llseek
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff815bba30-ffffffff815bba6b: kernfs_get_active (STB_GLOBAL)
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
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104530c4)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffff800010452f50-ffff800010452fd4: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615cd8)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
```
**Symbols:**

```
c0615ba0-c0615c10: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c350)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
c00000000056c1e0-c00000000056c248: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e577a)
Location: fs/kernfs/dir.c:413
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffe0002e577a-ffffffe0002e57da: kernfs_get_active (STB_GLOBAL)
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
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137ca58)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8137c980-ffffffff8137c9b0: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d528)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8136d450-ffffffff8136d480: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a528)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8137a450-ffffffff8137a480: kernfs_get_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_get_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e018)
Location: fs/kernfs/dir.c:413
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8138df40-ffffffff8138df70: kernfs_get_active (STB_GLOBAL)
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
