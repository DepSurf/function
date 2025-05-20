# Function: <code>__test_and_set_bit_le</code>

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
In fs/ext4/ialloc.c (ffffffff812947c5)
Location: include/asm-generic/bitops/le.h:87
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812c1dc0)
Location: include/asm-generic/bitops/le.h:87
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812d7422)
Location: include/asm-generic/bitops/le.h:87
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff812f57b6)
Location: include/asm-generic/bitops/le.h:87
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff81319f18)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/ialloc.c (ffffffff81347a05)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8138710d)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff8135fbb5)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8139fc1d)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff81388d2c)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813c9f0d)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff813a169f)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813e3213)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff813ed8ca)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814307b3)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff813fffeb)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144955c)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff814063a4)
Location: include/asm-generic/bitops/le.h:118
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8144eecc)
Location: include/asm-generic/bitops/le.h:118
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff81458c04)
Location: include/asm-generic/bitops/le.h:118
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff814a2a1b)
Location: include/asm-generic/bitops/le.h:118
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff814d67b3)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff81529e50)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff8156f577)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff815c87b6)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff815a73bf)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff8160056c)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff815e01fd)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff816392bc)
Location: include/asm-generic/bitops/le.h:54
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffff800010474e88)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffff8000104bc77c)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (c06364b8)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (c067fdec)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (c000000000596718)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (c0000000005f2524)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffe000300aca)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffe0003384be)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff81399c7f)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813db7f3)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff8138a70f)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813cc273)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff813974df)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813d8c93)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
In fs/ext4/ialloc.c (ffffffff813ab862)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/super.c (ffffffff813edf73)
Location: include/asm-generic/bitops/le.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
</ul>

## Differences
