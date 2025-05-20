# Function: <code>ext4_walk_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299850)
Location: fs/ext4/inode.c:830
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff81299850-ffffffff812998e9: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cda70)
Location: fs/ext4/inode.c:998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812c6ec0-ffffffff812c6f70: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e3840)
Location: fs/ext4/inode.c:1012
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff812dc9b0-ffffffff812dca60: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813079c0)
Location: fs/ext4/inode.c:1062
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff81301240-ffffffff813012dc: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132c610)
Location: fs/ext4/inode.c:1072
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff81325bf0-ffffffff81325c8e: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8135abe3)
Location: fs/ext4/inode.c:1073
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff81353e80-ffffffff81353f21: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81372ea3)
Location: fs/ext4/inode.c:1073
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff8136bfc0-ffffffff8136c061: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139c2f3)
Location: fs/ext4/inode.c:1081
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff81395580-ffffffff8139564d: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b4e03)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff813adf50-ffffffff813ae01d: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814002a0)
Location: fs/ext4/inode.c:939
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff813f9f20-ffffffff813f9fed: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412a9a)
Location: fs/ext4/inode.c:956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8140c520-ffffffff8140c5ed: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81418efa)
Location: fs/ext4/inode.c:957
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff814126a0-ffffffff8141276d: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct inode *inode, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct inode *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8146c12e)
Location: fs/ext4/inode.c:958
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff81465480-ffffffff81465552: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct inode *inode, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct inode *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814ec134)
Location: fs/ext4/inode.c:971
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff814e4de0-ffffffff814e4e88: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct inode *inode, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct inode *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81585e9e)
Location: fs/ext4/inode.c:977
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff8157e430-ffffffff8157e4d6: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct inode *inode, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct inode *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815bc780)
Location: fs/ext4/inode.c:932
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff815b5730-ffffffff815b57d6: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct inode *inode, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct inode *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f555f)
Location: fs/ext4/inode.c:946
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
**Symbols:**

```
ffffffff815ee4e0-ffffffff815ee586: ext4_walk_page_buffers (STB_GLOBAL)
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
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010489594)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffff8000104828e0-ffff8000104829d0: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064bac0)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
c0643d80-c0643e84: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005b05ec)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
c0000000005a7490-c0000000005a761c: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000310d50)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffe00030b1a4-ffffffe00030b236: ext4_walk_page_buffers (STB_GLOBAL)
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
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad3e3)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff813a6530-ffffffff813a65fd: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139de73)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff81396fc0-ffffffff8139708d: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813aac43)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff813a3d90-ffffffff813a3e5d: ext4_walk_page_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_walk_page_buffers(handle_t *handle, struct buffer_head *head, unsigned int from, unsigned int to, int *partial, int (*fn)(handle_t *, struct buffer_head *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bf58e)
Location: fs/ext4/inode.c:1090
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_journalled_write_end
```
**Symbols:**

```
ffffffff813b8460-ffffffff813b852d: ext4_walk_page_buffers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, head, from, to, partial, fn</code> ➡️ <code>handle, inode, head, from, to, partial, fn</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*fn)(handle_t *, struct buffer_head *)</code> ➡️ <code>int (*fn)(handle_t *, struct inode *, struct buffer_head *)</code>
</li>
</ul>
</details>
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
