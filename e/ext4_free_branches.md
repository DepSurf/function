# Function: <code>ext4_free_branches</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d8c70)
Location: fs/ext4/indirect.c:1093
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
```
**Symbols:**

```
ffffffff812d8c70-ffffffff812d8f2b: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81308a10)
Location: fs/ext4/indirect.c:981
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81308a10-ffffffff81308cd5: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131ea20)
Location: fs/ext4/indirect.c:981
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8131ea20-ffffffff8131ece5: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f7600)
Location: fs/ext4/indirect.c:982
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff812f7600-ffffffff812f7937: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131bc40)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8131bc40-ffffffff8131bf77: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81349b40)
Location: fs/ext4/indirect.c:989
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81349b40-ffffffff81349e8a: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81361d00)
Location: fs/ext4/indirect.c:989
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81361d00-ffffffff8136204a: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138b110)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8138b110-ffffffff8138b462: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a3b60)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813a3b60-ffffffff813a3eb2: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813efda0)
Location: fs/ext4/indirect.c:987
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813efda0-ffffffff813efffe: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81402500)
Location: fs/ext4/indirect.c:988
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81402500-ffffffff8140275c: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81408900)
Location: fs/ext4/indirect.c:988
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81408900-ffffffff81408b59: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145b370)
Location: fs/ext4/indirect.c:992
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8145b370-ffffffff8145b5d3: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d9130)
Location: fs/ext4/indirect.c:992
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff814d9130-ffffffff814d93c9: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81571f70)
Location: fs/ext4/indirect.c:999
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81571f70-ffffffff81572209: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a9d00)
Location: fs/ext4/indirect.c:1007
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff815a9d00-ffffffff815a9f99: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e2aa0)
Location: fs/ext4/indirect.c:1007
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff815e2aa0-ffffffff815e2d39: ext4_free_branches (STB_LOCAL)
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
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff8000104771d8)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffff8000104771d8-ffff800010477538: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0638d44)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
c0638d44-c06390d8: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c000000000599370)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
c000000000599370-c000000000599824: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe00030260a)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffe00030260a-ffffffe0003028f2: ext4_free_branches (STB_LOCAL)
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
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139c140)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8139c140-ffffffff8139c492: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138cbd0)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8138cbd0-ffffffff8138cf22: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813999a0)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813999a0-ffffffff81399cf2: ext4_free_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_free_branches(handle_t *handle, struct inode *inode, struct buffer_head *parent_bh, __le32 *first, __le32 *last, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ada90)
Location: fs/ext4/indirect.c:983
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813ada90-ffffffff813adde2: ext4_free_branches (STB_LOCAL)
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
