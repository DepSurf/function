# Function: <code>ext4_update_inode_size</code>

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
In fs/ext4/inode.c (ffffffff8129dcee)
Location: fs/ext4/ext4.h:2836
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/extents.c (ffffffff812c33d5)
Location: fs/ext4/ext4.h:2836
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/inode.c (ffffffff812cc7a6)
Location: fs/ext4/ext4.h:2871
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/extents.c (ffffffff812fa6d7)
Location: fs/ext4/ext4.h:2871
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/inode.c (ffffffff812e1658)
Location: fs/ext4/ext4.h:2849
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/extents.c (ffffffff81310695)
Location: fs/ext4/ext4.h:2849
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
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
In fs/ext4/extents.c (ffffffff812eecbd)
Location: fs/ext4/ext4.h:2867
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff81305a35)
Location: fs/ext4/ext4.h:2867
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813137c5)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8132a586)
Location: fs/ext4/ext4.h:2824
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813416b5)
Location: fs/ext4/ext4.h:2829
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8135894d)
Location: fs/ext4/ext4.h:2829
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff81358cef)
Location: fs/ext4/ext4.h:2856
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff81370c7e)
Location: fs/ext4/ext4.h:2856
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff8137a4e0)
Location: fs/ext4/ext4.h:2936
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8139a1c3)
Location: fs/ext4/ext4.h:2936
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813929b0)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813b2c83)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813df14b)
Location: fs/ext4/ext4.h:3109
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e8f5d)
Location: fs/ext4/ext4.h:3109
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff813ff325)
Location: fs/ext4/ext4.h:3109
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813f09ff)
Location: fs/ext4/ext4.h:3283
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813fadc3)
Location: fs/ext4/ext4.h:3283
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff81411aca)
Location: fs/ext4/ext4.h:3283
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813f6e99)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8140122f)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff81417eea)
Location: fs/ext4/ext4.h:3345
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff81449b6c)
Location: fs/ext4/ext4.h:3415
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8145379f)
Location: fs/ext4/ext4.h:3415
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145ebc3)
Location: fs/ext4/ext4.h:3415
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8146b1dc)
Location: fs/ext4/ext4.h:3415
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff814c6257)
Location: fs/ext4/ext4.h:3378
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d132a)
Location: fs/ext4/ext4.h:3378
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814dd327)
Location: fs/ext4/ext4.h:3378
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814eb266)
Location: fs/ext4/ext4.h:3378
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff8155e7e9)
Location: fs/ext4/ext4.h:3391
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81569e52)
Location: fs/ext4/ext4.h:3391
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff81576357)
Location: fs/ext4/ext4.h:3391
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81584e14)
Location: fs/ext4/ext4.h:3391
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff815965e9)
Location: fs/ext4/ext4.h:3370
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a1c4f)
Location: fs/ext4/ext4.h:3370
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815adc10)
Location: fs/ext4/ext4.h:3370
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815bb795)
Location: fs/ext4/ext4.h:3370
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff815cf282)
Location: fs/ext4/ext4.h:3390
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815da858)
Location: fs/ext4/ext4.h:3390
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815e69d0)
Location: fs/ext4/ext4.h:3390
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f4572)
Location: fs/ext4/ext4.h:3390
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffff8000104651ec)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffff8000104874e0)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (c06264ec)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (c0649538)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (c0000000005838d8)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (c0000000005ad90c)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffe0002f39ea)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffe00030f2d6)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff8138af90)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813ab263)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff8137ba20)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8139bcf3)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff813888f0)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813a8ac3)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
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
In fs/ext4/extents.c (ffffffff8139c5f0)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813bd373)
Location: fs/ext4/ext4.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
</details>
</li>
</ul>

## Differences
