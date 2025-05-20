# Function: <code>ext4_dir_rec_len</code>

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
In fs/ext4/dir.c (ffffffff813f3f08)
Location: fs/ext4/ext4.h:2298
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2298
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8142db64)
Location: fs/ext4/ext4.h:2298
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
In fs/ext4/dir.c (ffffffff81445ff4)
Location: fs/ext4/ext4.h:2368
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2368
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81481af8)
Location: fs/ext4/ext4.h:2368
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
In fs/ext4/dir.c (ffffffff814c2027)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2374
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81504ada)
Location: fs/ext4/ext4.h:2374
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
In fs/ext4/dir.c (ffffffff8155a293)
Location: fs/ext4/ext4.h:2384
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2384
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8159f68a)
Location: fs/ext4/ext4.h:2384
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
In fs/ext4/dir.c (ffffffff8159208d)
Location: fs/ext4/ext4.h:2378
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2378
Inline: True
```
```
In fs/ext4/namei.c (ffffffff815d5fb7)
Location: fs/ext4/ext4.h:2378
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
In fs/ext4/dir.c (ffffffff815cadfd)
Location: fs/ext4/ext4.h:2396
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (0)
Location: fs/ext4/ext4.h:2396
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8160e647)
Location: fs/ext4/ext4.h:2396
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:dx_pack_dirents
  - fs/ext4/namei.c:dx_move_dirents
  - fs/ext4/namei.c:htree_dirblock_to_tree
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
