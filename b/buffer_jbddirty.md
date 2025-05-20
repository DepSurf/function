# Function: <code>buffer_jbddirty</code>

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
In fs/jbd2/transaction.c (ffffffff812e925c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812eac40)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff812ec95d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff812f2b50)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff81316e4f)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813185ce)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8131a3cd)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81320520)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8132ce43)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff8132e5c4)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813303bd)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813363d0)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8134200c)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813436f1)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813452ef)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8134b100)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8136663c)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81367d45)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8136998f)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8136f750)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff81394da3)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813965c3)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8139812a)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8139dc70)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813adb13)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813af330)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813b0e9a)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813b69e0)
Location: include/linux/jbd2.h:328
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813d7e55)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813d985a)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813db4fa)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e10b8)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813f1f25)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813f3852)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813f554a)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813fb108)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8143f25a)
Location: include/linux/jbd2.h:324
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81440b81)
Location: include/linux/jbd2.h:324
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814428da)
Location: include/linux/jbd2.h:324
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81448873)
Location: include/linux/jbd2.h:324
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8145b4ba)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8145cdb6)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8145eaea)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81465488)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff81460dfa)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff814627bc)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8146437a)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8146ac18)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff814b62dd)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff814b7cb2)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff814b99ad)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814c1428)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff8153fbcb)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81541760)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81543679)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154bd68)
Location: include/linux/jbd2.h:331
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff815de73b)
Location: include/linux/jbd2.h:330
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff815e03a4)
Location: include/linux/jbd2.h:330
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff815e25b9)
Location: include/linux/jbd2.h:330
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815ebb38)
Location: include/linux/jbd2.h:330
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/ext4/page-io.c (ffffffff815daaa4)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff8161619f)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81617c50)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81619f29)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623618)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/ext4/page-io.c (ffffffff816132d6)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164efbc)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81650b3c)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652e89)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165c678)
Location: include/linux/jbd2.h:321
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffff8000104cc420)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffff8000104ce9e0)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d0f6c)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d86d8)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (c068fbcc)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c06918c0)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c0693ac4)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (c069a5b4)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (c0000000006057ec)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c000000000607990)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (c00000000060a17c)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (c000000000613504)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffe000344fa8)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffe000346756)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffe000348442)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffe00034e1f0)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813ea505)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813ebe32)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813edb2a)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f36e8)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813daf85)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813dc8b2)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813de5aa)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813e4168)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813e7885)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813e91b2)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff813eaeaa)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff813f0a68)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/jbd2/transaction.c (ffffffff813fd04d)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813fea98)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8140080a)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff814064d8)
Location: include/linux/jbd2.h:325
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
</details>
</li>
</ul>

## Differences
