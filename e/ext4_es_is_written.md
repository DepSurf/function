# Function: <code>ext4_es_is_written</code>

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
In fs/ext4/inode.c (ffffffff81298b72)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:108
Inline: True
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
In fs/ext4/inode.c (ffffffff812c5cb9)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff8130b226)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
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
In fs/ext4/inode.c (ffffffff812db4e9)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff81321226)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff812f0215)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff812ffd99)
Location: fs/ext4/extents_status.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents_status.c (ffffffff81314d25)
Location: fs/ext4/extents_status.h:109
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813245b5)
Location: fs/ext4/extents_status.h:109
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents_status.c (ffffffff81342c43)
Location: fs/ext4/extents_status.h:109
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813513bd)
Location: fs/ext4/extents_status.h:109
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents_status.c (ffffffff8135a713)
Location: fs/ext4/extents_status.h:161
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff8136a263)
Location: fs/ext4/extents_status.h:161
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81383633)
Location: fs/ext4/extents_status.h:161
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813941cd)
Location: fs/ext4/extents_status.h:161
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff8139bc87)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813acb61)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff813e76d4)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813f8e14)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff813f9994)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff8140b4a9)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff813ffd37)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff81411661)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81452353)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff81464437)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff814cf29c)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff814e3bb5)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81567b5c)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff8157d0b5)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff8159f059)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff815b4485)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff815d7bbe)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff815ed293)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffff80001046ea88)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffff800010481344)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (c063003c)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (c06423f4)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (c00000000058ed2c)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (c0000000005a5890)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffe0002fb8dc)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffe000309fc8)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81394267)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813a5141)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81384cf7)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff81395bd1)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff81391bc7)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813a29a1)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents_status.c (ffffffff813a5aa7)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff813b7081)
Location: fs/ext4/extents_status.h:162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_mapped
```
</details>
</li>
</ul>

## Differences
