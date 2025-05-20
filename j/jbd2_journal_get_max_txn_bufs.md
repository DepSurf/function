# Function: <code>jbd2_journal_get_max_txn_bufs</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8145cc9f)
Location: include/linux/jbd2.h:1630
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814650f6)
Location: include/linux/jbd2.h:1630
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff8146268d)
Location: include/linux/jbd2.h:1639
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8146a886)
Location: include/linux/jbd2.h:1639
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff814b7b83)
Location: include/linux/jbd2.h:1678
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814c1006)
Location: include/linux/jbd2.h:1678
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff81541620)
Location: include/linux/jbd2.h:1672
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81549f7a)
Location: include/linux/jbd2.h:1672
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff815e0285)
Location: include/linux/jbd2.h:1670
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff815ea81a)
Location: include/linux/jbd2.h:1670
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff81617b36)
Location: include/linux/jbd2.h:1671
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81620f61)
Location: include/linux/jbd2.h:1671
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_reset
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
In fs/jbd2/commit.c (ffffffff81650a07)
Location: include/linux/jbd2.h:1665
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81659ba1)
Location: include/linux/jbd2.h:1665
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_reset
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
