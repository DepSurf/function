# Function: <code>ext4_handle_has_enough_credits</code>

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
In fs/ext4/inode.c (ffffffff8129d954)
Location: fs/ext4/ext4_jbd2.h:290
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff812bf845)
Location: fs/ext4/ext4_jbd2.h:290
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812cc0ae)
Location: fs/ext4/ext4_jbd2.h:290
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/indirect.c (ffffffff812d8817)
Location: fs/ext4/ext4_jbd2.h:290
Inline: True
Inline callers:
  - fs/ext4/indirect.c:try_to_extend_transaction
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
In fs/ext4/inode.c (ffffffff812cb62b)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff812eed95)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff812fb9ea)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/indirect.c (ffffffff813085b2)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
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
In fs/ext4/inode.c (ffffffff812e130b)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/resize.c (ffffffff81304d65)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8131199a)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
Inline callers:
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/indirect.c (ffffffff8131e5a2)
Location: fs/ext4/ext4_jbd2.h:298
Inline: True
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
In fs/ext4/indirect.c (ffffffff812f772f)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81313e88)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81320415)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8133dc42)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff8131bd6f)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81338648)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81344ae5)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81362222)
Location: fs/ext4/ext4_jbd2.h:294
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff81349c6d)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff81366c02)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff81371d95)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81390a33)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff81361e2d)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff8137f07e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff8138a275)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813a9613)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff8138b1be)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813a8465)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b5145)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d3b2e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff813a3c0e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813c1327)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813cdc05)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813ed20e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/ext4/indirect.c (ffff80001047729c)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffff800010498084)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffff8000104a5e68)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c5eb4)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (c0638e08)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (c065a3d8)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0667e98)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (c0689ec4)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (c00000000059947c)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (c0000000005c2ae0)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (c0000000005d3b00)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (c0000000005fe2f8)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffe0003026a0)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffe00031c6fa)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffe000327190)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffe00034048c)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff8139c1ee)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b9907)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c61e5)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e57ee)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff8138cc7e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813aa397)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813b6c65)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813d626e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff81399a4e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813b7167)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813c3675)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813e2b6e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/indirect.c (ffffffff813adb3e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
```
In fs/ext4/migrate.c (ffffffff813cbe75)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:finish_range
```
```
In fs/ext4/resize.c (ffffffff813d8825)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff813f7f7e)
Location: fs/ext4/ext4_jbd2.h:291
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>

## Differences
