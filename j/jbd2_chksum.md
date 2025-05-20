# Function: <code>jbd2_chksum</code>

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
In fs/jbd2/commit.c (ffffffff812e9ba3)
Location: include/linux/jbd2.h:1472
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec132)
Location: include/linux/jbd2.h:1472
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed724)
Location: include/linux/jbd2.h:1472
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812ef817)
Location: include/linux/jbd2.h:1472
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_superblock_csum
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/commit.c (ffffffff81318265)
Location: include/linux/jbd2.h:1487
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319e24)
Location: include/linux/jbd2.h:1487
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8131e91f)
Location: include/linux/jbd2.h:1487
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8132e255)
Location: include/linux/jbd2.h:1487
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fe14)
Location: include/linux/jbd2.h:1487
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8133499f)
Location: include/linux/jbd2.h:1487
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8134323b)
Location: include/linux/jbd2.h:1489
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344dcd)
Location: include/linux/jbd2.h:1489
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813496ae)
Location: include/linux/jbd2.h:1489
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81367875)
Location: include/linux/jbd2.h:1595
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8136946d)
Location: include/linux/jbd2.h:1595
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8136dcfe)
Location: include/linux/jbd2.h:1595
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81395f7e)
Location: include/linux/jbd2.h:1595
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397a95)
Location: include/linux/jbd2.h:1595
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139c46e)
Location: include/linux/jbd2.h:1595
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff813aecd4)
Location: include/linux/jbd2.h:1596
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b081b)
Location: include/linux/jbd2.h:1596
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
In fs/jbd2/journal.c (ffffffff813b522e)
Location: include/linux/jbd2.h:1596
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813d91cf)
Location: include/linux/jbd2.h:1616
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dadae)
Location: include/linux/jbd2.h:1616
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
In fs/jbd2/journal.c (ffffffff813df8a4)
Location: include/linux/jbd2.h:1616
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813f31d1)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4dfe)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/journal.c (ffffffff813f9964)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff8143fd2a)
Location: include/linux/jbd2.h:1599
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff81441a4b)
Location: include/linux/jbd2.h:1599
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81447249)
Location: include/linux/jbd2.h:1599
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff8145bdfa)
Location: include/linux/jbd2.h:1734
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff8145e62d)
Location: include/linux/jbd2.h:1734
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
In fs/jbd2/journal.c (ffffffff814637a9)
Location: include/linux/jbd2.h:1734
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff81462450)
Location: include/linux/jbd2.h:1743
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463eba)
Location: include/linux/jbd2.h:1743
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
In fs/jbd2/journal.c (ffffffff814688f7)
Location: include/linux/jbd2.h:1743
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff814b7946)
Location: include/linux/jbd2.h:1782
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b948f)
Location: include/linux/jbd2.h:1782
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814be3a7)
Location: include/linux/jbd2.h:1782
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff815410f9)
Location: include/linux/jbd2.h:1774
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81542fff)
Location: include/linux/jbd2.h:1774
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81549e53)
Location: include/linux/jbd2.h:1774
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/commit.c (ffffffff815dfc40)
Location: include/linux/jbd2.h:1772
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1ddf)
Location: include/linux/jbd2.h:1772
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815ea6e5)
Location: include/linux/jbd2.h:1772
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/commit.c (ffffffff81617939)
Location: include/linux/jbd2.h:1773
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81619863)
Location: include/linux/jbd2.h:1773
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81620d82)
Location: include/linux/jbd2.h:1773
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/jbd2/commit.c (ffffffff816507d4)
Location: include/linux/jbd2.h:1786
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8165276f)
Location: include/linux/jbd2.h:1786
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff816599c2)
Location: include/linux/jbd2.h:1786
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_load_superblock
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
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (ffff8000104cd868)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104cfdc0)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d3c20)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_superblock_csum
```
**Symbols:**

```
ffff8000104cd868-ffff8000104cd86c: jbd2_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104cd870-ffff8000104cd8f4: jbd2_chksum.isra.0 (STB_LOCAL)
ffff8000104cfdc0-ffff8000104cfdc4: jbd2_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104cfdc8-ffff8000104cfe4c: jbd2_chksum.isra.0 (STB_LOCAL)
ffff8000104d3c20-ffff8000104d3c24: jbd2_chksum.isra.0.part.0 (STB_LOCAL)
ffff8000104d3c28-ffff8000104d3cac: jbd2_chksum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
u32 jbd2_chksum(journal_t *journal, u32 crc, const void *address, unsigned int length);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/commit.c (c0690804)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0692884)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c0697030)
Location: include/linux/jbd2.h:1614
Inline: True
Direct callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
**Symbols:**

```
c0690804-c0690814: jbd2_chksum.part.0 (STB_LOCAL)
c0690814-c06908a8: jbd2_chksum (STB_LOCAL)
c0692884-c0692894: jbd2_chksum.part.0 (STB_LOCAL)
c0692894-c0692928: jbd2_chksum (STB_LOCAL)
c0697030-c0697040: jbd2_chksum.part.0 (STB_LOCAL)
c0697040-c06970d4: jbd2_chksum (STB_LOCAL)
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
In fs/jbd2/commit.c (c000000000607368)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000609910)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000610af0)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/commit.c (ffffffe0003463f0)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347d1c)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034c4c2)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_superblock_csum
  - fs/jbd2/journal.c:jbd2_superblock_csum
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
In fs/jbd2/commit.c (ffffffff813eb7b1)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed3de)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/journal.c (ffffffff813f1f44)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813dc231)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dde5e)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/journal.c (ffffffff813e29c4)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813e8b31)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea75e)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/journal.c (ffffffff813ef2c4)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
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
In fs/jbd2/commit.c (ffffffff813fe38d)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814000c5)
Location: include/linux/jbd2.h:1614
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
In fs/jbd2/journal.c (ffffffff81404c88)
Location: include/linux/jbd2.h:1614
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
