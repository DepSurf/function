# Function: <code>ext4_has_feature_64bit</code>

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
In fs/ext4/inode.c (ffffffff81299f91)
Location: fs/ext4/ext4.h:1712
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812adb8f)
Location: fs/ext4/ext4.h:1712
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/inode.c (ffffffff812c7e85)
Location: fs/ext4/ext4.h:1780
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff812eb5dd)
Location: fs/ext4/ext4.h:1780
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff812ddbd3)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff81301540)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff81301a84)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff813363ee)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff81326444)
Location: fs/ext4/ext4.h:1730
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8135a96d)
Location: fs/ext4/ext4.h:1730
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff81354918)
Location: fs/ext4/ext4.h:1733
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/super.c (ffffffff8138910b)
Location: fs/ext4/ext4.h:1733
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff8136cc5d)
Location: fs/ext4/ext4.h:1746
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813a19be)
Location: fs/ext4/ext4.h:1746
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff8139622f)
Location: fs/ext4/ext4.h:1766
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813cc4b5)
Location: fs/ext4/ext4.h:1766
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff813aec1f)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813e583d)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff813fac9f)
Location: fs/ext4/ext4.h:1920
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff814329a6)
Location: fs/ext4/ext4.h:1920
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff8140d30e)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8144b7ae)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff814134cb)
Location: fs/ext4/ext4.h:2054
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff81451200)
Location: fs/ext4/ext4.h:2054
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff81466800)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff814a4809)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff814e636f)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff8152c51d)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff8157fb06)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff815cb2a4)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff815b6fa8)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff815fc9bb)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff815efd48)
Location: fs/ext4/ext4.h:2145
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff816354db)
Location: fs/ext4/ext4.h:2145
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_check_feature_compatibility
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffff8000104835c4)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffff8000104becdc)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (c0644a18)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c0682754)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (c0000000005a863c)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (c0000000005f522c)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffe00030bd62)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffe00033a60a)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff813a71ff)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813dde1d)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff81397c8f)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813ce89d)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff813a4a5f)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813db292)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
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
In fs/ext4/inode.c (ffffffff813b9164)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/super.c (ffffffff813f058d)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
```
</details>
</li>
</ul>

## Differences
