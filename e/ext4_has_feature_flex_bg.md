# Function: <code>ext4_has_feature_flex_bg</code>

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
In fs/ext4/balloc.c (ffffffff8128f095)
Location: fs/ext4/ext4.h:1714
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/super.c (ffffffff812bcebd)
Location: fs/ext4/ext4.h:1714
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812c0c5d)
Location: fs/ext4/ext4.h:1714
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/balloc.c (ffffffff812bc5c7)
Location: fs/ext4/ext4.h:1782
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/super.c (ffffffff812ebe6b)
Location: fs/ext4/ext4.h:1782
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812f052d)
Location: fs/ext4/ext4.h:1782
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/balloc.c (ffffffff812d1c17)
Location: fs/ext4/ext4.h:1767
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/super.c (ffffffff81301e2e)
Location: fs/ext4/ext4.h:1767
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff813064fd)
Location: fs/ext4/ext4.h:1767
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/balloc.c (ffffffff812e32cd)
Location: fs/ext4/ext4.h:1772
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/resize.c (ffffffff81320ea4)
Location: fs/ext4/ext4.h:1772
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81336d39)
Location: fs/ext4/ext4.h:1772
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/balloc.c (ffffffff81307cbd)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/resize.c (ffffffff813455da)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8135b2dd)
Location: fs/ext4/ext4.h:1732
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/balloc.c (ffffffff81335bb2)
Location: fs/ext4/ext4.h:1735
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8137368e)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81389a8c)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/balloc.c (ffffffff8134ce32)
Location: fs/ext4/ext4.h:1748
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8138ba83)
Location: fs/ext4/ext4.h:1748
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a260b)
Location: fs/ext4/ext4.h:1748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/balloc.c (ffffffff81375842)
Location: fs/ext4/ext4.h:1768
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813b66cf)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813cd8c0)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff8138daa1)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813cf5ff)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e734d)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff813d8e6d)
Location: fs/ext4/ext4.h:1922
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/resize.c (ffffffff814192cc)
Location: fs/ext4/ext4.h:1922
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814343ea)
Location: fs/ext4/ext4.h:1922
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff813eaa7d)
Location: fs/ext4/ext4.h:2047
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8141cce9)
Location: fs/ext4/ext4.h:2047
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff8142d2ed)
Location: fs/ext4/ext4.h:2047
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144cdde)
Location: fs/ext4/ext4.h:2047
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff813f0fa5)
Location: fs/ext4/ext4.h:2056
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8142335a)
Location: fs/ext4/ext4.h:2056
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff81433fb7)
Location: fs/ext4/ext4.h:2056
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814528ce)
Location: fs/ext4/ext4.h:2056
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff81442f05)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81476bae)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff814879ba)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a5eed)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff814bed25)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814f8eeb)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff8150b27c)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152dd0c)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff81556c15)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8159363b)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff815a5e42)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815cbecd)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff8158e9d5)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815ca6b6)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff815dc6b2)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816037f3)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff815c76e5)
Location: fs/ext4/ext4.h:2147
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff816034c6)
Location: fs/ext4/ext4.h:2147
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/resize.c (ffffffff81614f92)
Location: fs/ext4/ext4.h:2147
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8163c60b)
Location: fs/ext4/ext4.h:2147
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffff80001045fa18)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffff8000104a7f2c)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104bfe78)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (c0620254)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (c066a1dc)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0683bb0)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (c00000000057bce0)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (c0000000005d5880)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005f66fc)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffe0002ef17e)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffe0003284a4)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033b6d4)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff81386081)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813c7bdf)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813df92d)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff81376b11)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813b865f)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d03ad)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff81383b51)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813c506f)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dcc9d)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
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
In fs/ext4/balloc.c (ffffffff8139767b)
Location: fs/ext4/ext4.h:1825
Inline: True
```
```
In fs/ext4/resize.c (ffffffff813da263)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f20bb)
Location: fs/ext4/ext4.h:1825
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_check_descriptors
```
</details>
</li>
</ul>

## Differences
