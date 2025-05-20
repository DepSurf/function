# Function: <code>ext4_verity_in_progress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b2258)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff813cc638)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813eebe3)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff813fdec0)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff814187f7)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8143bd80)
Location: fs/ext4/ext4.h:1753
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff81410610)
Location: fs/ext4/ext4.h:1870
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff8142c33d)
Location: fs/ext4/ext4.h:1870
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff814580e0)
Location: fs/ext4/ext4.h:1870
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff814169d0)
Location: fs/ext4/ext4.h:1879
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff81433034)
Location: fs/ext4/ext4.h:1879
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8145dc40)
Location: fs/ext4/ext4.h:1879
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff81469f50)
Location: fs/ext4/ext4.h:1941
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff81486954)
Location: fs/ext4/ext4.h:1941
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff814b3100)
Location: fs/ext4/ext4.h:1941
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff814e9e57)
Location: fs/ext4/ext4.h:1943
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff8150a22d)
Location: fs/ext4/ext4.h:1943
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153baf1)
Location: fs/ext4/ext4.h:1943
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff81583977)
Location: fs/ext4/ext4.h:1953
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff815a4d7a)
Location: fs/ext4/ext4.h:1953
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815da171)
Location: fs/ext4/ext4.h:1953
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff815ba365)
Location: fs/ext4/ext4.h:1947
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/verity.c (ffffffff81611eb4)
Location: fs/ext4/ext4.h:1947
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff815f30d5)
Location: fs/ext4/ext4.h:1965
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/verity.c (ffffffff8164ac54)
Location: fs/ext4/ext4.h:1965
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffff800010486b80)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffff8000104a4afc)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffff8000104c860c)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (c0648ac0)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (c06666f4)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (c068bdfc)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (c0000000005acba8)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:mpage_submit_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (c0000000005d1c5c)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (c000000000600a60)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffe00030ea9e)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffe000325c1c)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffe000341e98)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff813aa838)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff813c4c18)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e71c3)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff8139b2c8)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff813b5698)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813d7c43)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff813a8098)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff813c20a8)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e4543)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
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
In fs/ext4/inode.c (ffffffff813bc918)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_process_page_bufs
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/readpage.c (ffffffff813d7228)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813f9953)
Location: fs/ext4/ext4.h:1658
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
</details>
</li>
</ul>

## Differences
