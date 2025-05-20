# Function: <code>ext4_hash_in_dirent</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f3f12)
Location: fs/ext4/ext4.h:2244
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff8140cc1c)
Location: fs/ext4/ext4.h:2244
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142db66)
Location: fs/ext4/ext4.h:2244
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
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
In fs/ext4/dir.c (ffffffff81445ffe)
Location: fs/ext4/ext4.h:2314
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff8145fa6c)
Location: fs/ext4/ext4.h:2314
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81481afa)
Location: fs/ext4/ext4.h:2314
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
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
In fs/ext4/dir.c (ffffffff814c2031)
Location: fs/ext4/ext4.h:2320
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff814de108)
Location: fs/ext4/ext4.h:2320
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81504adc)
Location: fs/ext4/ext4.h:2320
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
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
In fs/ext4/dir.c (ffffffff8155a29d)
Location: fs/ext4/ext4.h:2330
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff81577168)
Location: fs/ext4/ext4.h:2330
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8159f68c)
Location: fs/ext4/ext4.h:2330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
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
In fs/ext4/dir.c (ffffffff81592097)
Location: fs/ext4/ext4.h:2324
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff815ae709)
Location: fs/ext4/ext4.h:2324
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815d5fb9)
Location: fs/ext4/ext4.h:2324
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
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
In fs/ext4/dir.c (ffffffff815cae07)
Location: fs/ext4/ext4.h:2342
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff815e74c9)
Location: fs/ext4/ext4.h:2342
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8160e649)
Location: fs/ext4/ext4.h:2342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
