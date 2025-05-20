# Function: <code>jbd2_journal_has_csum_v2or3_feature</code>

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
In fs/jbd2/commit.c (ffffffff812e9b4a)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb7d5)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed699)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff812f101e)
Location: include/linux/jbd2.h:1408
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/jbd2/commit.c (ffffffff813177e4)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319d02)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8131b5e5)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8131e80e)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff8132d7d4)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fcf2)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813315d5)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8133488e)
Location: include/linux/jbd2.h:1423
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff8134297d)
Location: include/linux/jbd2.h:1425
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344cab)
Location: include/linux/jbd2.h:1425
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81346545)
Location: include/linux/jbd2.h:1425
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81349563)
Location: include/linux/jbd2.h:1425
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff81366fad)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8136934b)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8136abcd)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8136dbb3)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813958a9)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397a43)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81399373)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8139c364)
Location: include/linux/jbd2.h:1531
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813ae5e9)
Location: include/linux/jbd2.h:1532
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b07c9)
Location: include/linux/jbd2.h:1532
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b20e3)
Location: include/linux/jbd2.h:1532
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813b5124)
Location: include/linux/jbd2.h:1532
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813d8aa9)
Location: include/linux/jbd2.h:1552
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dad63)
Location: include/linux/jbd2.h:1552
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dc742)
Location: include/linux/jbd2.h:1552
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813df7b3)
Location: include/linux/jbd2.h:1552
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813f2a99)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4db3)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813f6806)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f9873)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff8143c789)
Location: include/linux/jbd2.h:1554
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff814401a7)
Location: include/linux/jbd2.h:1554
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff81441a0d)
Location: include/linux/jbd2.h:1554
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff81443511)
Location: include/linux/jbd2.h:1554
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
```
```
In fs/jbd2/journal.c (ffffffff81447159)
Location: include/linux/jbd2.h:1554
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff81458b69)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff8145c337)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff8145dcd6)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8145f5f1)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
```
```
In fs/jbd2/journal.c (ffffffff814636b9)
Location: include/linux/jbd2.h:1682
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff8145e4ee)
Location: include/linux/jbd2.h:1691
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff814619ab)
Location: include/linux/jbd2.h:1691
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463d9f)
Location: include/linux/jbd2.h:1691
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8146547d)
Location: include/linux/jbd2.h:1691
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81468819)
Location: include/linux/jbd2.h:1691
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff814b435c)
Location: include/linux/jbd2.h:1730
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff814b6e9b)
Location: include/linux/jbd2.h:1730
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b9371)
Location: include/linux/jbd2.h:1730
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff814badfd)
Location: include/linux/jbd2.h:1730
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff814be2c9)
Location: include/linux/jbd2.h:1730
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff8153dbec)
Location: include/linux/jbd2.h:1724
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8154093a)
Location: include/linux/jbd2.h:1724
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81542fd2)
Location: include/linux/jbd2.h:1724
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff81544ccc)
Location: include/linux/jbd2.h:1724
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff815499c5)
Location: include/linux/jbd2.h:1724
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff815dc45c)
Location: include/linux/jbd2.h:1722
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff815df53a)
Location: include/linux/jbd2.h:1722
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1db2)
Location: include/linux/jbd2.h:1722
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff815e3e0c)
Location: include/linux/jbd2.h:1722
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff815e8fa2)
Location: include/linux/jbd2.h:1722
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff81613f0e)
Location: include/linux/jbd2.h:1723
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81616d28)
Location: include/linux/jbd2.h:1723
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8161970d)
Location: include/linux/jbd2.h:1723
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8161b5c7)
Location: include/linux/jbd2.h:1723
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81620780)
Location: include/linux/jbd2.h:1723
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/transaction.c (ffffffff8164ccfe)
Location: include/linux/jbd2.h:1736
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8164fb41)
Location: include/linux/jbd2.h:1736
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81652627)
Location: include/linux/jbd2.h:1736
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff816544e7)
Location: include/linux/jbd2.h:1736
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81659f89)
Location: include/linux/jbd2.h:1736
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:journal_check_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffff8000104cdf84)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d06ac)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffff8000104d28dc)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffff8000104d5fa0)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (c0690b54)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c06933d0)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (c0695054)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c06979bc)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (c000000000606b18)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006098d0)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (c00000000060c168)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c000000000610a60)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffe000345b30)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347cae)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffe00034985e)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffe00034c42a)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813eb079)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed393)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813eede6)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f1e53)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813dbaf9)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dde13)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813df866)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813e28d3)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813e83f9)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea713)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813ec166)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813ef1d3)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813fdc19)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8140007d)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81401b06)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81404ba2)
Location: include/linux/jbd2.h:1550
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
</details>
</li>
</ul>

## Differences
