# Function: <code>ext4_rec_len_from_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81290ee0)
Location: fs/ext4/ext4.h:1906
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812a4c95)
Location: fs/ext4/ext4.h:1906
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
```
```
In fs/ext4/inline.c (ffffffff812e1ca1)
Location: fs/ext4/ext4.h:1906
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812be458)
Location: fs/ext4/ext4.h:1980
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812d5856)
Location: fs/ext4/ext4.h:1980
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
```
```
In fs/ext4/inline.c (ffffffff813123ca)
Location: fs/ext4/ext4.h:1980
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d3aaf)
Location: fs/ext4/ext4.h:1965
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812eb556)
Location: fs/ext4/ext4.h:1965
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
```
```
In fs/ext4/inline.c (ffffffff8132832a)
Location: fs/ext4/ext4.h:1965
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e5481)
Location: fs/ext4/ext4.h:1984
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff812fc261)
Location: fs/ext4/ext4.h:1984
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813191f3)
Location: fs/ext4/ext4.h:1984
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81309ea4)
Location: fs/ext4/ext4.h:1944
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813209b1)
Location: fs/ext4/ext4.h:1944
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8133d933)
Location: fs/ext4/ext4.h:1944
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813387ac)
Location: fs/ext4/ext4.h:1947
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134eb09)
Location: fs/ext4/ext4.h:1947
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8136e012)
Location: fs/ext4/ext4.h:1947
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8134fa5c)
Location: fs/ext4/ext4.h:1960
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81366c89)
Location: fs/ext4/ext4.h:1960
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81386492)
Location: fs/ext4/ext4.h:1960
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813786df)
Location: fs/ext4/ext4.h:1982
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81390042)
Location: fs/ext4/ext4.h:1982
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813b04e0)
Location: fs/ext4/ext4.h:1982
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81390a9f)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a8aa2)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c94bb)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813dc0d7)
Location: fs/ext4/ext4.h:2138
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f4b49)
Location: fs/ext4/ext4.h:2138
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81414d5e)
Location: fs/ext4/ext4.h:2138
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813edb67)
Location: fs/ext4/ext4.h:2263
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814072b9)
Location: fs/ext4/ext4.h:2263
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff814283ae)
Location: fs/ext4/ext4.h:2263
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f41cf)
Location: fs/ext4/ext4.h:2313
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff8140d729)
Location: fs/ext4/ext4.h:2313
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142eeae)
Location: fs/ext4/ext4.h:2313
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/dir.c (ffffffff8144630f)
Location: fs/ext4/ext4.h:2383
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff814605c4)
Location: fs/ext4/ext4.h:2383
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8148397e)
Location: fs/ext4/ext4.h:2383
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/dir.c (ffffffff814c241c)
Location: fs/ext4/ext4.h:2389
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff814def4c)
Location: fs/ext4/ext4.h:2389
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81506b00)
Location: fs/ext4/ext4.h:2389
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/dir.c (ffffffff8155a69c)
Location: fs/ext4/ext4.h:2399
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (ffffffff8157801c)
Location: fs/ext4/ext4.h:2399
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815a15f0)
Location: fs/ext4/ext4.h:2399
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/dir.c (ffffffff81591dd4)
Location: fs/ext4/ext4.h:2393
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815af504)
Location: fs/ext4/ext4.h:2393
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815d7f70)
Location: fs/ext4/ext4.h:2393
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
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
In fs/ext4/dir.c (ffffffff815cab44)
Location: fs/ext4/ext4.h:2411
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e82c4)
Location: fs/ext4/ext4.h:2411
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff816105e0)
Location: fs/ext4/ext4.h:2411
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_handle_dirty_dx_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff8000104633f4)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047c350)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffff8000104a1048)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c0623b70)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063dd80)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c065dedc)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c000000000580454)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/inline.c (c00000000059fc58)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0000000005c7044)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f1e5c)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000306468)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffe00032312a)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8138907f)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a1082)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c1a9b)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81379b0f)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81391b12)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813b252b)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813869df)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e8e2)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813bef4b)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8139a6bf)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b2e52)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813d402b)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
</ul>

## Differences
