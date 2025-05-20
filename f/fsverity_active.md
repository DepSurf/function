# Function: <code>fsverity_active</code>

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
In fs/ext4/inode.c (ffffffff813b32d1)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffff813cca79)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/file.c (ffffffff813e96ca)
Location: include/linux/fsverity.h:214
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814189b7)
Location: include/linux/fsverity.h:214
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/file.c (ffffffff813fb37a)
Location: include/linux/fsverity.h:219
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c5cd)
Location: include/linux/fsverity.h:219
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/file.c (ffffffff8140184a)
Location: include/linux/fsverity.h:231
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814332a6)
Location: include/linux/fsverity.h:231
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/file.c (ffffffff81453dda)
Location: include/linux/fsverity.h:231
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486d55)
Location: include/linux/fsverity.h:231
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/file.c (ffffffff814d175e)
Location: include/linux/fsverity.h:249
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_supported
```
```
In fs/ext4/readpage.c (ffffffff8150a5cf)
Location: include/linux/fsverity.h:249
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffff815806b5)
Location: include/linux/fsverity.h:252
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
```
In fs/ext4/readpage.c (ffffffff815a5066)
Location: include/linux/fsverity.h:252
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff8150adca)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
```
In fs/ext4/inode.c (ffffffff815b7c75)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
```
In fs/ext4/readpage.c (ffffffff815dbbe6)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff8153fc8a)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
```
In fs/ext4/inode.c (ffffffff815f09f5)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
```
In fs/ext4/readpage.c (ffffffff816144ad)
Location: include/linux/fsverity.h:279
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffff800010487b20)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffff8000104a4d14)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (c0649cd0)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (c0666adc)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (c0000000005ae180)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (c0000000005d20b0)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffe00030f462)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffe000325f1c)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffff813ab8b1)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffff813c5059)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffff8139c341)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffff813b5ad9)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffff813a9111)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffff813c24e9)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/inode.c (ffffffff813bd9c1)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/readpage.c (ffffffff813d7679)
Location: include/linux/fsverity.h:206
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>

## Differences
