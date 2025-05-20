# Function: <code>ext4_has_feature_journal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b82ca)
Location: fs/ext4/ext4.h:1687
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812eccad)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81302a9e)
Location: fs/ext4/ext4.h:1740
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/super.c (ffffffff813372e8)
Location: fs/ext4/ext4.h:1745
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/super.c (ffffffff8135cdbb)
Location: fs/ext4/ext4.h:1705
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/super.c (ffffffff8138648c)
Location: fs/ext4/ext4.h:1708
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/super.c (ffffffff8139ef8c)
Location: fs/ext4/ext4.h:1721
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81377442)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff8137979a)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff81391455)
Location: fs/ext4/ext4.h:1741
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff8139d9dd)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c9608)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff8138f792)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff81391cba)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff813a9dd5)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff813b64a5)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813e2908)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff813dacb5)
Location: fs/ext4/ext4.h:1893
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff813f5665)
Location: fs/ext4/ext4.h:1893
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff8140248a)
Location: fs/ext4/ext4.h:1893
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8142f715)
Location: fs/ext4/ext4.h:1893
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff813ec9bb)
Location: fs/ext4/ext4.h:2017
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff81407e25)
Location: fs/ext4/ext4.h:2017
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff81414d62)
Location: fs/ext4/ext4.h:2017
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81448445)
Location: fs/ext4/ext4.h:2017
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff813f2efb)
Location: fs/ext4/ext4.h:2026
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff8140e1a5)
Location: fs/ext4/ext4.h:2026
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff8141ae08)
Location: fs/ext4/ext4.h:2026
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8144dc95)
Location: fs/ext4/ext4.h:2026
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81444eeb)
Location: fs/ext4/ext4.h:2091
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff81461075)
Location: fs/ext4/ext4.h:2091
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff8146e15b)
Location: fs/ext4/ext4.h:2091
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff814a1d25)
Location: fs/ext4/ext4.h:2091
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff814c0f3b)
Location: fs/ext4/ext4.h:2093
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff814dffe5)
Location: fs/ext4/ext4.h:2093
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff814ee4ef)
Location: fs/ext4/ext4.h:2093
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81528f85)
Location: fs/ext4/ext4.h:2093
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff815590eb)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff81579285)
Location: fs/ext4/ext4.h:2103
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff815883ef)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815c70a5)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81590f3b)
Location: fs/ext4/ext4.h:2097
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff815b0785)
Location: fs/ext4/ext4.h:2097
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff815bf203)
Location: fs/ext4/ext4.h:2097
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815fee25)
Location: fs/ext4/ext4.h:2097
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff815c9c7b)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/inode.c (ffffffff815e9575)
Location: fs/ext4/ext4.h:2115
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff815f7fa9)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81637a25)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffff8000104620a0)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffff8000104654cc)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffff80001047dbdc)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffff80001048bc78)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffff8000104bbd64)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (c0622644)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (c0624b4c)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (c063fce4)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (c064d5d0)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c067f3b0)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (c00000000057e9fc)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (c000000000581944)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (c0000000005a29d0)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (c0000000005b25cc)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0000000005f16e4)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffe0002f0f4a)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffe0002f2ab0)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffe000307a36)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffe000312028)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffe000337b5a)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81387d72)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff8138a29a)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff813a23b5)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff813aea85)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813daee8)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81378802)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff8137ad2a)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff81392e45)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff8139f515)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813cb968)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff81385842)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff81387bfa)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff8139fc15)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff813ac2e5)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d8388)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/block_validity.c (ffffffff813993d2)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/extents.c (ffffffff8139b8da)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/inode.c (ffffffff813b48f5)
Location: fs/ext4/ext4.h:1797
Inline: True
```
```
In fs/ext4/ioctl.c (ffffffff813c0c85)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813ed628)
Location: fs/ext4/ext4.h:1797
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
</ul>

## Differences
