# Function: <code>clear_buffer_new</code>

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
In fs/buffer.c (ffffffff8124322a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
```
```
In fs/ext4/balloc.c (ffffffff8128f4ce)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81297756)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff812a00ee)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff812e9277)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812eb12d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8126de2a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff812bc9de)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cca13)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812cea7d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81316e67)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81318b87)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff81281050)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff812d202e)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dab43)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e4873)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8132ce5b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff8132eb7e)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8128e93c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff812e369f)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fe970)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8131e5a0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81342024)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81343b72)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff812b1515)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff8130808f)
Location: include/linux/buffer_head.h:124
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81323135)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81342be9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81366654)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813681c5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff812d936e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81335f76)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81350f62)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81370931)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81394dbb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813969f8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff812ee83e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff8134d1f6)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81368fb2)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81388dba)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813adb2b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813af761)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8131003f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81375be2)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813923d9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b2cab)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813d7e70)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813d9caf)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8132300f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff8138de52)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aad69)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813cbd19)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813f1f40)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813f3d4d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8135dda1)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff813d9352)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813f6bee)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81418147)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8143f270)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8144118c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8136b95f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff813eafe2)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814092df)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142bb7b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8145b4d0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8145d38d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff81372280)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff813f152a)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140f2af)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81432844)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81460e10)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81462cb6)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff813c12b7)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff8144352a)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814622bd)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81486104)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff814b62f3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff814b81ac)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff81447deb)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff814bf358)
Location: include/linux/buffer_head.h:126
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e16ce)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8150942e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8153fbe6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81541c32)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff814d6999)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81557296)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff8157a9de)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815a3fec)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff815de756)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff815e087e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8150cfac)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/balloc.c (ffffffff8158f116)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b0b29)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815daa3f)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff816161ba)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81618186)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8153d2b2)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/balloc.c (ffffffff815c7e26)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815e99c9)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8161324c)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164efd7)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff816510c0)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffff8000103dc454)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffff80001045ff4c)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffff80001047f458)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffff8000104a40f4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffff8000104cc448)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffff8000104cf368)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (c05b5740)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (c0620760)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (c064067c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0666078)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c068fbf4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c0692044)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (c0000000004e1910)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (c00000000057c298)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a31a4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0000000005d0fcc)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c000000000605820)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c00000000060803c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffe0002946f8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffe0002ef630)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffe000308428)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffe0003253c6)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffe000344fc2)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffe000346dd4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8131b5ef)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81386432)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a3349)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c42f9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813ea520)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813ec32d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8130c18f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81376ec2)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81393dd9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b4d79)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813dafa0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813dcdad)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff813190bf)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81383f02)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a0ba9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c1789)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813e78a0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813e96ad)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8132acfc)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff81397a6d)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b579d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813d68e9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813fd065)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813fefa1)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
</details>
</li>
</ul>

## Differences
