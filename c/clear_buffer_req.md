# Function: <code>clear_buffer_req</code>

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
In fs/buffer.c (ffffffff8124425a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:unmap_underlying_metadata
```
```
In fs/jbd2/transaction.c (ffffffff812e9272)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812eb133)
Location: include/linux/buffer_head.h:120
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
In fs/buffer.c (ffffffff8126c53a)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:unmap_underlying_metadata
```
```
In fs/jbd2/transaction.c (ffffffff81316e62)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81318b8b)
Location: include/linux/buffer_head.h:120
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
In fs/buffer.c (ffffffff8127ef54)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8132ce56)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff8132eb82)
Location: include/linux/buffer_head.h:120
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
In fs/buffer.c (ffffffff8128c8b1)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8134201f)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81343b78)
Location: include/linux/buffer_head.h:120
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
In fs/buffer.c (ffffffff812af40d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8136664f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813681cb)
Location: include/linux/buffer_head.h:121
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
In fs/buffer.c (ffffffff812d6f9c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff81394db6)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813969fe)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff812ec31f)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813adb26)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813af767)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff8130d96b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813d7e6a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813d9cb5)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff8132093b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813f1f3a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813f3d53)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81359bb9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8143f26c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81441191)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81367ce9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8145b4cc)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8145d392)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff8136e4f9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff81460e0c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81462cbb)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff813bd0dd)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff814b62ef)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff814b81b1)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81443ecb)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8153fbe0)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81541c36)
Location: include/linux/buffer_head.h:123
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
In fs/buffer.c (ffffffff814d286d)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff815de750)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff815e0882)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff8150917b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff816161b4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8161818a)
Location: include/linux/buffer_head.h:127
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
In fs/buffer.c (ffffffff8153ddad)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff8164efd1)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff816510c5)
Location: include/linux/buffer_head.h:125
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
In fs/buffer.c (ffff8000103d7c48)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffff8000104cc438)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffff8000104cf374)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (c05b25b4)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (c068fbe8)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c0692050)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (c0000000004dde30)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (c00000000060580c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c00000000060804c)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffe000292154)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffe000344fbc)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffe000346ddc)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81318f1b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813ea51a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813ec333)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81309b0b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813daf9a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813dcdb3)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff813169eb)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813e789a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813e96b3)
Location: include/linux/buffer_head.h:124
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
In fs/buffer.c (ffffffff81328925)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/jbd2/transaction.c (ffffffff813fd060)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813fefa5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
</details>
</li>
</ul>

## Differences
