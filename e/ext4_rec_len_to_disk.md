# Function: <code>ext4_rec_len_to_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a1a00)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/namei.c:initialize_dirent_tail
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
Direct callers:
  - fs/ext4/namei.c:initialize_dirent_tail
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_init_dot_dotdot
```
```
In fs/ext4/inline.c (ffffffff812dfae0)
Location: fs/ext4/ext4.h:1919
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812a1a00-ffffffff812a1a06: ext4_rec_len_to_disk.part.11 (STB_LOCAL)
ffffffff812dfae0-ffffffff812dfae6: ext4_rec_len_to_disk.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d5a2f)
Location: fs/ext4/ext4.h:1993
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
```
In fs/ext4/inline.c (ffffffff813118e3)
Location: fs/ext4/ext4.h:1993
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812d0930-ffffffff812d0936: ext4_rec_len_to_disk.part.12 (STB_LOCAL)
ffffffff8130f780-ffffffff8130f786: ext4_rec_len_to_disk.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff812eb72f)
Location: fs/ext4/ext4.h:1978
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
```
In fs/ext4/inline.c (ffffffff81327823)
Location: fs/ext4/ext4.h:1978
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812e66d0-ffffffff812e66d6: ext4_rec_len_to_disk.part.14 (STB_LOCAL)
ffffffff813255a0-ffffffff813255a6: ext4_rec_len_to_disk.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fb73e)
Location: fs/ext4/ext4.h:1997
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8131b3c0)
Location: fs/ext4/ext4.h:1997
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
**Symbols:**

```
ffffffff812fcbd5-ffffffff812fcbdb: ext4_rec_len_to_disk.part.7 (STB_LOCAL)
ffffffff813162e0-ffffffff813162e6: ext4_rec_len_to_disk.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131feb1)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8133facf)
Location: fs/ext4/ext4.h:1957
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
**Symbols:**

```
ffffffff81321435-ffffffff8132143b: ext4_rec_len_to_disk.part.8 (STB_LOCAL)
ffffffff8133ab50-ffffffff8133ab56: ext4_rec_len_to_disk.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134dfd7)
Location: fs/ext4/ext4.h:1960
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8136da7f)
Location: fs/ext4/ext4.h:1960
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
**Symbols:**

```
ffffffff8134bd70-ffffffff8134bd76: ext4_rec_len_to_disk.part.10 (STB_LOCAL)
ffffffff813690c0-ffffffff813690c6: ext4_rec_len_to_disk.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81366177)
Location: fs/ext4/ext4.h:1973
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81385eff)
Location: fs/ext4/ext4.h:1973
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:initialize_dirent_tail
```
**Symbols:**

```
ffffffff81363eb0-ffffffff81363eb6: ext4_rec_len_to_disk.part.10 (STB_LOCAL)
ffffffff81381560-ffffffff81381566: ext4_rec_len_to_disk.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f4f9)
Location: fs/ext4/ext4.h:1995
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813afedf)
Location: fs/ext4/ext4.h:1995
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff8138cdc0-ffffffff8138cdc2: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813aa800-ffffffff813aa802: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a7f57)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c8e9f)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff813a5810-ffffffff813a5812: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813c3730-ffffffff813c3732: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f4001)
Location: fs/ext4/ext4.h:2151
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81414a3f)
Location: fs/ext4/ext4.h:2151
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff813f14b0-ffffffff813f14b2: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff8140fd00-ffffffff8140fd02: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81406791)
Location: fs/ext4/ext4.h:2276
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142808f)
Location: fs/ext4/ext4.h:2276
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff81403b90-ffffffff81403b92: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff814230a0-ffffffff814230a2: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140cc6b)
Location: fs/ext4/ext4.h:2326
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142eba4)
Location: fs/ext4/ext4.h:2326
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff8140a230-ffffffff8140a232: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff81429920-ffffffff81429922: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145fabb)
Location: fs/ext4/ext4.h:2396
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81483345)
Location: fs/ext4/ext4.h:2396
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814de0a0)
Location: fs/ext4/ext4.h:2402
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815064a5)
Location: fs/ext4/ext4.h:2402
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81577100)
Location: fs/ext4/ext4.h:2412
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815a0f65)
Location: fs/ext4/ext4.h:2412
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ae791)
Location: fs/ext4/ext4.h:2406
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815d78e5)
Location: fs/ext4/ext4.h:2406
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e7551)
Location: fs/ext4/ext4.h:2424
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8160ff55)
Location: fs/ext4/ext4.h:2424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffff80001047b834)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffff8000104a0988)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffff800010478d80-ffff800010478d84: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffff80001049b058-ffff80001049b05c: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (c063d0bc)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0662ae0)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
c063acc4-c063acd4: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
c065cbd4-c065cbe4: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (c00000000059ed68)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0000000005ccea4)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
c00000000059bc40-c00000000059bc44: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
c0000000005c5b10-c0000000005c5b14: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffe000305c3e)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffe000322bd8)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffe000303efc-ffffffe000303f04: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffe00031e642-ffffffe00031e64a: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a0537)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c147f)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff8139ddf0-ffffffff8139ddf2: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813bbd10-ffffffff813bbd12: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390fc7)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813b1f0f)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff8138e880-ffffffff8138e882: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813ac7a0-ffffffff813ac7a2: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139dd97)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813be92f)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff8139b650-ffffffff8139b652: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813b9600-ffffffff813b9602: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b2307)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813d3a0f)
Location: fs/ext4/ext4.h:2053
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
Direct callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_initialize_dirent_tail
```
**Symbols:**

```
ffffffff813afb10-ffffffff813afb12: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
ffffffff813ce290-ffffffff813ce292: ext4_rec_len_to_disk.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
