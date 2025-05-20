# Function: <code>test_clear_buffer_dirty</code>

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
In fs/buffer.c (ffffffff81244fd7)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
```
```
In fs/jbd2/transaction.c (ffffffff812e8335)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8126dbb7)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff81316015)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff81280e07)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff8132c005)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8128e6e7)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff81341205)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff812b12d7)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff8136582b)
Location: include/linux/buffer_head.h:119
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff812d913a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff81393fc8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff812ee60a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813accfa)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8130fe01)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813d6f5f)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff81322dd1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813f0fbc)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8135d840)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff8143e547)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8136b430)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff8145a7e7)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff81371cd0)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff81460073)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff813c0cf0)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff814b54f3)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8144799e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff8153ee4d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff814d64fe)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff815dd82f)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8150ca6e)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/jbd2/transaction.c (ffffffff8161526f)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff815416de)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164e05f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffff8000103dbf48)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffff8000104cae64)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (c05b5258)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (c068e7d4)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (c0000000004e3c98)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (c000000000603df8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffe000294414)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffe000343e6e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8131b3b1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813e959c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8130bf51)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813da01c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff81318e81)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813e691c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
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
In fs/buffer.c (ffffffff8132aab1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:__block_write_full_page
```
```
In fs/jbd2/transaction.c (ffffffff813fbeac)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
```
</details>
</li>
</ul>

## Differences
