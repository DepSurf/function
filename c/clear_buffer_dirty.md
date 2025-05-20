# Function: <code>clear_buffer_dirty</code>

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
In fs/buffer.c (ffffffff8124349f)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__bforget
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:block_invalidatepage
```
```
In fs/mpage.c (ffffffff8124d700)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81296759)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8129fe99)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff812e8578)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812e9be7)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8126d400)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81275e50)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c6fa7)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff812ce795)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81316e4a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317e14)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff8128065a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81289b30)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dca97)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff812e4575)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8132ce3e)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132ddfc)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff8128df49)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81296830)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81301318)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8131e2b7)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81342007)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342f5c)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff812b0b58)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff812b9a94)
Location: include/linux/buffer_head.h:118
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81325cc8)
Location: include/linux/buffer_head.h:118
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813428d7)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81366637)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367587)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff812d897c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff812e2604)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81353f67)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8137075d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81394d9e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395d73)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff812ede51)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff812f7264)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136c0a7)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81388be8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813adb0e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeac9)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8130f62e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81317880)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81395680)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813b2cd5)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813d7e4f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d9059)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff813225a3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff8132a700)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813ae050)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813cbd43)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813f1f1f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3052)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8135c842)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff813643c0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813fa03f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff81418009)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8143f256)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8144088a)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8136acea)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff813713c0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140c63f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff8142bb06)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8145b4b6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cab7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff813703fe)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81377d70)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814127bf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff814327cd)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81460df6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8146214c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff813bef6c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff813c4430)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814655b7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff8148608d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff814b62d9)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b7642)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff814476b0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff8144bea4)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e4ebf)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff81509457)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff81525508)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff8153fbc5)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540e0c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff814d62e7)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff814daa29)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
```
In fs/ext4/inode.c (ffffffff8157e51f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff815a3ffb)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff815c2b66)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff815de735)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815dff5c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff8150b71e)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff8150effb)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
```
```
In fs/ext4/inode.c (ffffffff815b581f)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff815daa4e)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff815fa2c6)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff81616199)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617275)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffffffff815404de)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81543830)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff815ee5cf)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:do_journal_get_write_access
```
```
In fs/ext4/page-io.c (ffffffff8161325b)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/super.c (ffffffff81632ec6)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/transaction.c (ffffffff8164efb6)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650090)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
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
In fs/buffer.c (ffff8000103db470)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffff8000103e5ed4)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffff800010482a84)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffff8000104a4038)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffff8000104cc410)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce6d0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (c05b4880)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (c05bd9f0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (c0643f24)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (c0665f40)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c068fbc0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c06913a0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (c0000000004e076c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (c0000000004ec030)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a7674)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (c0000000005d121c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c0000000006057d8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607158)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffe000293c7c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffe00029b2fe)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffe00030b26c)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffe0003253c4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffe000344fa2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000346056)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8131ab83)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81322ce0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a6630)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813c4323)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813ea4ff)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb632)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8130b723)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff81313880)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813970c0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813b4da3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813daf7f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc0b2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff81318653)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff813207b0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a3e90)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813c17b3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813e787f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e89b2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/buffer.c (ffffffff8132a265)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bforget
```
```
In fs/mpage.c (ffffffff813324d0)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b8560)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813d6913)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813fd048)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe20a)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
</details>
</li>
</ul>

## Differences
