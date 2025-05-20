# Function: <code>jbd2_has_feature_csum3</code>

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
In fs/jbd2/commit.c (ffffffff812e9c27)
Location: include/linux/jbd2.h:1101
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eb849)
Location: include/linux/jbd2.h:1101
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed6ad)
Location: include/linux/jbd2.h:1101
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff812f0f37)
Location: include/linux/jbd2.h:1101
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_tag_bytes
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
In fs/jbd2/commit.c (ffffffff81317a5b)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81319d26)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8131b5fd)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81320405)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
In fs/jbd2/commit.c (ffffffff8132da4b)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132fd16)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813315ed)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813362b5)
Location: include/linux/jbd2.h:1116
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
In fs/jbd2/commit.c (ffffffff81342b91)
Location: include/linux/jbd2.h:1118
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81344cc4)
Location: include/linux/jbd2.h:1118
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81346559)
Location: include/linux/jbd2.h:1118
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8134afe5)
Location: include/linux/jbd2.h:1118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
In fs/jbd2/commit.c (ffffffff813671c1)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81369364)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8136abe9)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8136f635)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
In fs/jbd2/commit.c (ffffffff813958af)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397a4e)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813992b7)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8139db5d)
Location: include/linux/jbd2.h:1223
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813ae5ef)
Location: include/linux/jbd2.h:1224
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b07d4)
Location: include/linux/jbd2.h:1224
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b2027)
Location: include/linux/jbd2.h:1224
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813b68cd)
Location: include/linux/jbd2.h:1224
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813d8aaf)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dad6e)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dc688)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813e0f8d)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813f2a9f)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4dbe)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813f66d8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813fafdd)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143c78f)
Location: include/linux/jbd2.h:1241
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff814401a9)
Location: include/linux/jbd2.h:1241
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff81441a16)
Location: include/linux/jbd2.h:1241
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff81443528)
Location: include/linux/jbd2.h:1241
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
```
```
In fs/jbd2/journal.c (ffffffff81448795)
Location: include/linux/jbd2.h:1241
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff81458b6f)
Location: include/linux/jbd2.h:1347
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff8145c339)
Location: include/linux/jbd2.h:1347
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff8145dcdb)
Location: include/linux/jbd2.h:1347
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8145f608)
Location: include/linux/jbd2.h:1347
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:write_one_revoke_record
```
```
In fs/jbd2/journal.c (ffffffff81465345)
Location: include/linux/jbd2.h:1347
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff8145e4f4)
Location: include/linux/jbd2.h:1356
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_get_transaction
```
```
In fs/jbd2/commit.c (ffffffff814619bd)
Location: include/linux/jbd2.h:1356
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463da1)
Location: include/linux/jbd2.h:1356
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff81465496)
Location: include/linux/jbd2.h:1356
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8146aad5)
Location: include/linux/jbd2.h:1356
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff814b435e)
Location: include/linux/jbd2.h:1384
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff814b6ead)
Location: include/linux/jbd2.h:1384
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b9373)
Location: include/linux/jbd2.h:1384
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff814bae16)
Location: include/linux/jbd2.h:1384
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff814c12e5)
Location: include/linux/jbd2.h:1384
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff8153dbf2)
Location: include/linux/jbd2.h:1381
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81540940)
Location: include/linux/jbd2.h:1381
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81542fdf)
Location: include/linux/jbd2.h:1381
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff81544cee)
Location: include/linux/jbd2.h:1381
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8154bbf5)
Location: include/linux/jbd2.h:1381
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff815dc462)
Location: include/linux/jbd2.h:1380
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff815df540)
Location: include/linux/jbd2.h:1380
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1dbf)
Location: include/linux/jbd2.h:1380
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff815e3e2e)
Location: include/linux/jbd2.h:1380
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff815eb995)
Location: include/linux/jbd2.h:1380
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/transaction.c (ffffffff81613f14)
Location: include/linux/jbd2.h:1379
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff81616d2a)
Location: include/linux/jbd2.h:1379
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81619716)
Location: include/linux/jbd2.h:1379
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8161b5ed)
Location: include/linux/jbd2.h:1379
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff81623475)
Location: include/linux/jbd2.h:1379
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164cd04)
Location: include/linux/jbd2.h:1376
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffffffff8164fb47)
Location: include/linux/jbd2.h:1376
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81652630)
Location: include/linux/jbd2.h:1376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (ffffffff8165450d)
Location: include/linux/jbd2.h:1376
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff8165c4d5)
Location: include/linux/jbd2.h:1376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:journal_revoke_records_per_block
  - fs/jbd2/journal.c:journal_check_superblock
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
In fs/jbd2/commit.c (ffff8000104cdf90)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d06b8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffff8000104d28f4)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffff8000104d8530)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (c0690b58)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c06933d4)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:count_tags
```
```
In fs/jbd2/revoke.c (c0694f1c)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c069a470)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (c000000000606b1c)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006098dc)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (c00000000060c180)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (c0000000006132f8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffe000345b52)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347cb8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffe000349884)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffe00034e04c)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/commit.c (ffffffff813eb07f)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed39e)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813eecb8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f35bd)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813dbaff)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dde1e)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813df738)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813e403d)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813e83ff)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea71e)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813ec038)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff813f093d)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813fdc1f)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81400088)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff814019d8)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_write_revoke_records
```
```
In fs/jbd2/journal.c (ffffffff814063ad)
Location: include/linux/jbd2.h:1237
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_tag_bytes
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
</details>
</li>
</ul>

## Differences
