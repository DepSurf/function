# Function: <code>kernfs_put_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a5c0)
Location: fs/kernfs/dir.c:472
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/file.c:kernfs_seq_stop_active
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
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8128a5c0-ffffffff8128a603: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7a00)
Location: fs/kernfs/dir.c:471
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff812b7a00-ffffffff812b7a44: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd190)
Location: fs/kernfs/dir.c:421
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff812cd190-ffffffff812cd1d4: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da770)
Location: fs/kernfs/dir.c:431
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff812da770-ffffffff812da7b4: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fefd0)
Location: fs/kernfs/dir.c:432
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff812fefd0-ffffffff812ff016: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cc60)
Location: fs/kernfs/dir.c:432
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8132cc60-ffffffff8132cca5: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81343fd0)
Location: fs/kernfs/dir.c:432
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff81343fd0-ffffffff81344015: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c220)
Location: fs/kernfs/dir.c:431
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8136c220-ffffffff8136c263: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813843d0)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff813843d0-ffffffff81384413: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813ceeb0)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_file_direct_read
  - fs/kernfs/file.c:kernfs_file_direct_read
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813ceeb0-ffffffff813ceef3: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0ae0)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813e0ae0-ffffffff813e0b23: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7610)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff813e7610-ffffffff813e7653: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439320)
Location: fs/kernfs/dir.c:435
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff81439320-ffffffff81439363: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4360)
Location: fs/kernfs/dir.c:442
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff814b4360-ffffffff814b43bf: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b200)
Location: fs/kernfs/dir.c:453
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff8154b200-ffffffff8154b25f: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582e50)
Location: fs/kernfs/dir.c:450
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff81582e50-ffffffff81582eaf: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bba80)
Location: fs/kernfs/dir.c:454
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_file_read_iter
  - fs/kernfs/file.c:kernfs_seq_stop
  - fs/kernfs/file.c:kernfs_seq_next
  - fs/kernfs/file.c:kernfs_seq_start
```
**Symbols:**

```
ffffffff815bba80-ffffffff815bbadf: kernfs_put_active (STB_GLOBAL)
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
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452fd8)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffff800010452fd8-ffff800010453068: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615c10)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
c0615c10-c0615c80: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c250)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_mmap
  - fs/kernfs/file.c:kernfs_vma_get_policy
  - fs/kernfs/file.c:kernfs_vma_set_policy
  - fs/kernfs/file.c:kernfs_vma_access
  - fs/kernfs/file.c:kernfs_vma_page_mkwrite
  - fs/kernfs/file.c:kernfs_vma_fault
  - fs/kernfs/file.c:kernfs_vma_open
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
c00000000056c250-c00000000056c2e8: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e61e8)
Location: fs/kernfs/dir.c:433
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffe0002e4a2e-ffffffe0002e4a6a: kernfs_put_active.part.0 (STB_LOCAL)
ffffffe0002e59f8-ffffffe0002e5a3c: kernfs_put_active (STB_GLOBAL)
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
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137c9b0)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8137c9b0-ffffffff8137c9f3: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d480)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8136d480-ffffffff8136d4c3: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a480)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8137a480-ffffffff8137a4c3: kernfs_put_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put_active(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138df70)
Location: fs/kernfs/dir.c:433
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
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
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_seq_stop_active
```
**Symbols:**

```
ffffffff8138df70-ffffffff8138dfb3: kernfs_put_active (STB_GLOBAL)
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
