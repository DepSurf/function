# Function: <code>ext4_has_feature_bigalloc</code>

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
In fs/ext4/ioctl.c (ffffffff812a052a)
Location: fs/ext4/ext4.h:1701
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812bb716)
Location: fs/ext4/ext4.h:1701
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:1701
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff812d9015)
Location: fs/ext4/ext4.h:1701
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/ioctl.c (ffffffff812cfaf0)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812eb9bf)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:1769
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff81308dce)
Location: fs/ext4/ext4.h:1769
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/ioctl.c (ffffffff812e5895)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813019e3)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:1754
Inline: True
```
```
In fs/ext4/indirect.c (ffffffff8131edde)
Location: fs/ext4/ext4.h:1754
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
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
In fs/ext4/indirect.c (ffffffff812f7a26)
Location: fs/ext4/ext4.h:1759
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813089d0)
Location: fs/ext4/ext4.h:1759
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:1759
Inline: True
```
```
In fs/ext4/super.c (ffffffff81336877)
Location: fs/ext4/ext4.h:1759
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/indirect.c (ffffffff8131c066)
Location: fs/ext4/ext4.h:1719
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8132d56c)
Location: fs/ext4/ext4.h:1719
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4.h:1719
Inline: True
```
```
In fs/ext4/super.c (ffffffff8135ae70)
Location: fs/ext4/ext4.h:1719
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/indirect.c (ffffffff8134a009)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8135bbd6)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff81366e57)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff81389757)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
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
In fs/ext4/indirect.c (ffffffff813621cf)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81373f4f)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff8137f2c6)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813a22ee)
Location: fs/ext4/ext4.h:1735
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff8138b65d)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8139e181)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813a8747)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813ccc0a)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff813a40ad)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813b6f6f)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813c1634)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813e60cd)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff813f01e2)
Location: fs/ext4/ext4.h:1908
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8140262f)
Location: fs/ext4/ext4.h:1908
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff8140d914)
Location: fs/ext4/ext4.h:1908
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff814331cd)
Location: fs/ext4/ext4.h:1908
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff814028f3)
Location: fs/ext4/ext4.h:2033
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81414f07)
Location: fs/ext4/ext4.h:2033
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff81420d74)
Location: fs/ext4/ext4.h:2033
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff8144bfd0)
Location: fs/ext4/ext4.h:2033
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff81408cf7)
Location: fs/ext4/ext4.h:2042
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8141aef2)
Location: fs/ext4/ext4.h:2042
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff81427534)
Location: fs/ext4/ext4.h:2042
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff814518d8)
Location: fs/ext4/ext4.h:2042
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff8145b771)
Location: fs/ext4/ext4.h:2108
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8146dd55)
Location: fs/ext4/ext4.h:2108
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff8147b1b4)
Location: fs/ext4/ext4.h:2108
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff814a4f4e)
Location: fs/ext4/ext4.h:2108
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff814d95d8)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814eed09)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff814fd616)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/resize.c (ffffffff8150ee06)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
```
```
In fs/ext4/super.c (ffffffff8152ced3)
Location: fs/ext4/ext4.h:2110
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff815723d8)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81588b4b)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff81597de6)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/resize.c (ffffffff815a9ca6)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815cbb92)
Location: fs/ext4/ext4.h:2120
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff815aa168)
Location: fs/ext4/ext4.h:2114
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815bf777)
Location: fs/ext4/ext4.h:2114
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff815ce855)
Location: fs/ext4/ext4.h:2114
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/resize.c (ffffffff815e0506)
Location: fs/ext4/ext4.h:2114
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8160361e)
Location: fs/ext4/ext4.h:2114
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff815e2f08)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815f851d)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff816070d5)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/resize.c (ffffffff81618fe6)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8163c439)
Location: fs/ext4/ext4.h:2132
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_handle_clustersize
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffff8000104779f4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffff80001048c6e8)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffff800010498af8)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffff8000104bf408)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (c06391e0)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (c064d2d8)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (c065a6f4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (c0682f34)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (c000000000599ad4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (c0000000005b27e4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (c0000000005c2e8c)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (c0000000005f5a94)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffe0003029d4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffe000312928)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/migrate.c (ffffffe00031c9fc)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffe00033a702)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff8139c68d)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813af54f)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813b9c14)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813de6ad)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff8138d11d)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8139ffdf)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813aa6a4)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813cf12d)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
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
In fs/ext4/indirect.c (ffffffff81399eed)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813acdaf)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813b7474)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813dba6a)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_feature_set_ok
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
In fs/ext4/indirect.c (ffffffff813adf8a)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813c174f)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/migrate.c (ffffffff813cc184)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/super.c (ffffffff813f0e1d)
Location: fs/ext4/ext4.h:1811
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
</ul>

## Differences
