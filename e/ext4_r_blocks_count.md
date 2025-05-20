# Function: <code>ext4_r_blocks_count</code>

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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:2723
Inline: True
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/ext4.h:2723
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: fs/ext4/ext4.h:2723
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
In fs/ext4/balloc.c (ffffffff812bc36e)
Location: fs/ext4/ext4.h:2758
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/super.c (ffffffff812e1190)
Location: fs/ext4/ext4.h:2758
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/resize.c (ffffffff812f03ff)
Location: fs/ext4/ext4.h:2758
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/balloc.c (ffffffff812d19be)
Location: fs/ext4/ext4.h:2736
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/super.c (ffffffff812f6cc0)
Location: fs/ext4/ext4.h:2736
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
```
```
In fs/ext4/resize.c (ffffffff813063cf)
Location: fs/ext4/ext4.h:2736
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
In fs/ext4/balloc.c (ffffffff812e302e)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff81320d72)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8132b5a0)
Location: fs/ext4/ext4.h:2752
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81307a5e)
Location: fs/ext4/ext4.h:2709
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813454a8)
Location: fs/ext4/ext4.h:2709
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8134fa00)
Location: fs/ext4/ext4.h:2709
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff8133594b)
Location: fs/ext4/ext4.h:2714
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff8137354f)
Location: fs/ext4/ext4.h:2714
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138343b)
Location: fs/ext4/ext4.h:2714
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff8134cbcb)
Location: fs/ext4/ext4.h:2741
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff8138b944)
Location: fs/ext4/ext4.h:2741
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8139be5b)
Location: fs/ext4/ext4.h:2741
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff813755eb)
Location: fs/ext4/ext4.h:2821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813b6590)
Location: fs/ext4/ext4.h:2821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813c49a8)
Location: fs/ext4/ext4.h:2821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff8138d869)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813cf4c0)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ddd28)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff813d8d22)
Location: fs/ext4/ext4.h:2994
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff8141919d)
Location: fs/ext4/ext4.h:2994
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81427688)
Location: fs/ext4/ext4.h:2994
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff813ea925)
Location: fs/ext4/ext4.h:3170
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff8142d15d)
Location: fs/ext4/ext4.h:3170
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8143f482)
Location: fs/ext4/ext4.h:3170
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff813f0e45)
Location: fs/ext4/ext4.h:3232
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff81433e2d)
Location: fs/ext4/ext4.h:3232
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144a4ef)
Location: fs/ext4/ext4.h:3232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81442d9b)
Location: fs/ext4/ext4.h:3302
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff814877ec)
Location: fs/ext4/ext4.h:3302
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8149dfab)
Location: fs/ext4/ext4.h:3302
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff814beb9b)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff8150b0ac)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815225ab)
Location: fs/ext4/ext4.h:3265
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81556a7b)
Location: fs/ext4/ext4.h:3278
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff815a5c9c)
Location: fs/ext4/ext4.h:3278
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815bf3cb)
Location: fs/ext4/ext4.h:3278
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff8158e83b)
Location: fs/ext4/ext4.h:3270
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff815dc50c)
Location: fs/ext4/ext4.h:3270
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815f658b)
Location: fs/ext4/ext4.h:3270
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff815c754b)
Location: fs/ext4/ext4.h:3290
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff81614dec)
Location: fs/ext4/ext4.h:3290
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8162ee8b)
Location: fs/ext4/ext4.h:3290
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffff80001045f7fc)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffff8000104a7df0)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104b8388)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (c061ff54)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (c0669fdc)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0675954)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (c00000000057ba08)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (c0000000005d5738)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005e5678)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffe0002eefc4)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffe00032839a)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033163a)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81385e49)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813c7aa0)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d6308)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff813768d9)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813b8520)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813c6d88)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81383919)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813c4f30)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d3798)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
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
In fs/ext4/balloc.c (ffffffff81397439)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
```
```
In fs/ext4/resize.c (ffffffff813da120)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e4798)
Location: fs/ext4/ext4.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
  - fs/ext4/super.c:ext4_statfs
```
</details>
</li>
</ul>

## Differences
