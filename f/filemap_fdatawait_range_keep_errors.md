# Function: <code>filemap_fdatawait_range_keep_errors</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213640)
Location: mm/filemap.c:566
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81213640-ffffffff81213674: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220e10)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81220e10-ffffffff81220e44: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e850)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:journal_finish_inode_data_buffers
```
**Symbols:**

```
ffffffff8124e850-ffffffff8124e887: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258d10)
Location: mm/filemap.c:573
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff81258d10-ffffffff81258d47: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d1c0)
Location: mm/filemap.c:564
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff8125d1c0-ffffffff8125d1f7: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299110)
Location: mm/filemap.c:582
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff81299110-ffffffff8129914d: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812efda0)
Location: mm/filemap.c:570
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff812efda0-ffffffff812efde7: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135af90)
Location: mm/filemap.c:567
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff8135af90-ffffffff8135afd7: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138dc90)
Location: mm/filemap.c:574
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff8138dc90-ffffffff8138dcd1: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b73d0)
Location: mm/filemap.c:569
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_finish_inode_data_buffers
  - fs/jbd2/commit.c:jbd2_wait_inode_data
```
**Symbols:**

```
ffffffff813b73d0-ffffffff813b7411: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae838)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffff8000102ae838-ffff8000102ae8a0: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dadd8)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c04dadd8-c04dae2c: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362740)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c000000000362740-c0000000003627b8: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4608)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffe0001d4608-ffffffe0001d4658: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219460)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81219460-ffffffff81219494: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c670)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8120c670-ffffffff8120c6a4: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217200)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81217200-ffffffff81217234: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filemap_fdatawait_range_keep_errors(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226290)
Location: mm/filemap.c:572
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81226290-ffffffff812262c4: filemap_fdatawait_range_keep_errors (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
