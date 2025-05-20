# Function: <code>get_slot_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435bc6)
Location: lib/radix-tree.c:94
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452be5)
Location: lib/radix-tree.c:99
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2d25)
Location: lib/radix-tree.c:120
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8197918f)
Location: lib/radix-tree.c:120
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d5766)
Location: lib/radix-tree.c:121
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d731)
Location: lib/radix-tree.c:102
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7d062)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab4392)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eed34)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81613484)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6adf)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816641df)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177e47c)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203b07c)
Location: lib/radix-tree.c:81
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b955c)
Location: lib/radix-tree.c:80
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193e6c)
Location: lib/radix-tree.c:80
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e8b4)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e88fd4)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed1550)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b72c4)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a531e2)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a102e2)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf5d2)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acbaa2)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
</ul>

## Differences
