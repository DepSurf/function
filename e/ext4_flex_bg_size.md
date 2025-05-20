# Function: <code>ext4_flex_bg_size</code>

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
In fs/ext4/balloc.c (ffffffff8129031a)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/ialloc.c (ffffffff81293087)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff812cf707)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
```
```
In fs/ext4/block_validity.c (ffffffff812d630c)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812bd83a)
Location: fs/ext4/ext4.h:2838
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/ialloc.c (ffffffff812c1977)
Location: fs/ext4/ext4.h:2838
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff812ff127)
Location: fs/ext4/ext4.h:2838
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
```
```
In fs/ext4/block_validity.c (ffffffff81305fac)
Location: fs/ext4/ext4.h:2838
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812d2e8a)
Location: fs/ext4/ext4.h:2816
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/ialloc.c (ffffffff812d6fb4)
Location: fs/ext4/ext4.h:2816
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813151a7)
Location: fs/ext4/ext4.h:2816
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
```
```
In fs/ext4/block_validity.c (ffffffff8131bf6c)
Location: fs/ext4/ext4.h:2816
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
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
In fs/ext4/balloc.c (ffffffff812e449a)
Location: fs/ext4/ext4.h:2834
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff812e4b2e)
Location: fs/ext4/ext4.h:2834
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff812f52db)
Location: fs/ext4/ext4.h:2834
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff8130c60e)
Location: fs/ext4/ext4.h:2834
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81308ec9)
Location: fs/ext4/ext4.h:2791
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff8130955e)
Location: fs/ext4/ext4.h:2791
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81319a4e)
Location: fs/ext4/ext4.h:2791
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813311de)
Location: fs/ext4/ext4.h:2791
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81336e05)
Location: fs/ext4/ext4.h:2796
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff8133745a)
Location: fs/ext4/ext4.h:2796
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813477b2)
Location: fs/ext4/ext4.h:2796
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff8135f6f1)
Location: fs/ext4/ext4.h:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff8134e085)
Location: fs/ext4/ext4.h:2823
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff8134e6da)
Location: fs/ext4/ext4.h:2823
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8135f962)
Location: fs/ext4/ext4.h:2823
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff81377b91)
Location: fs/ext4/ext4.h:2823
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81376a36)
Location: fs/ext4/ext4.h:2903
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff813770f9)
Location: fs/ext4/ext4.h:2903
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81388b14)
Location: fs/ext4/ext4.h:2903
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813a1014)
Location: fs/ext4/ext4.h:2903
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff8138eca6)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff8138f376)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813a148a)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813b9e9b)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff813da256)
Location: fs/ext4/ext4.h:3076
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff813da8a3)
Location: fs/ext4/ext4.h:3076
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813ec705)
Location: fs/ext4/ext4.h:3076
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff81403b21)
Location: fs/ext4/ext4.h:3076
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff813ebf26)
Location: fs/ext4/ext4.h:3250
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff813ec573)
Location: fs/ext4/ext4.h:3250
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813fe945)
Location: fs/ext4/ext4.h:3250
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff81416d66)
Location: fs/ext4/ext4.h:3250
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff813f2456)
Location: fs/ext4/ext4.h:3312
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff813f2ab3)
Location: fs/ext4/ext4.h:3312
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81404d35)
Location: fs/ext4/ext4.h:3312
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff8141d2f6)
Location: fs/ext4/ext4.h:3312
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81444432)
Location: fs/ext4/ext4.h:3382
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81444a82)
Location: fs/ext4/ext4.h:3382
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81457532)
Location: fs/ext4/ext4.h:3382
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff8146fd30)
Location: fs/ext4/ext4.h:3382
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff814c0312)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff814c0a22)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff814d5084)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff814f1390)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81558362)
Location: fs/ext4/ext4.h:3358
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81558b02)
Location: fs/ext4/ext4.h:3358
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8156dd64)
Location: fs/ext4/ext4.h:3358
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff8158b920)
Location: fs/ext4/ext4.h:3358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff815901ae)
Location: fs/ext4/ext4.h:3337
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81590952)
Location: fs/ext4/ext4.h:3337
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff815a5c54)
Location: fs/ext4/ext4.h:3337
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff815c156a)
Location: fs/ext4/ext4.h:3337
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff815c8eee)
Location: fs/ext4/ext4.h:3357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/ialloc.c (ffffffff815deac4)
Location: fs/ext4/ext4.h:3357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff815f981a)
Location: fs/ext4/ext4.h:3357
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
```
```
In fs/ext4/resize.c (ffffffff81618fac)
Location: fs/ext4/ext4.h:3357
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
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
In fs/ext4/balloc.c (ffff800010461220)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffff800010461c1c)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffff800010474ca8)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffff8000104906d8)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (c06218b8)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (c0622110)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (c06362a8)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (c0651804)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (c00000000057d928)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (c00000000057e3bc)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (c000000000596498)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (c0000000005b7d30)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffe0002f04c0)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffe0002f0b62)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffe0003006da)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffe00031565e)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81387286)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81387956)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff81399a6a)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813b247b)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81377d16)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff813783e6)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff8138a4fa)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813a2f0b)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff81384d56)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81385426)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813972ca)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813afcdb)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
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
In fs/ext4/balloc.c (ffffffff813988d6)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/block_validity.c (ffffffff81398fa7)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/ialloc.c (ffffffff813ab5ee)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
```
```
In fs/ext4/mballoc.c (ffffffff813c470a)
Location: fs/ext4/ext4.h:2965
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
```
</details>
</li>
</ul>

## Differences
