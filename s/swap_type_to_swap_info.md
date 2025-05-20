# Function: <code>swap_type_to_swap_info</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278084)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81287b74)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812b9f34)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff812c59a4)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff812cc654)
Location: mm/swapfile.c:100
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff8131197d)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff8137cafd)
Location: mm/swapfile.c:103
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff813fa31d)
Location: mm/swapfile.c:107
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff8142d24d)
Location: mm/swapfile.c:108
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
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
In mm/swapfile.c (ffffffff814669ed)
Location: mm/swapfile.c:110
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_folio_sector
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
In mm/swapfile.c (ffff800010322924)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (c053ae88)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (c0000000003f8358)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffe0002236e8)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81280154)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff81271fc4)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8127df64)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
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
In mm/swapfile.c (ffffffff8128db14)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_next
  - mm/swapfile.c:swap_start
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:get_swap_page_of_type
```
</details>
</li>
</ul>

## Differences
