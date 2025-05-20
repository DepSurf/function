# Function: <code>jbd2_journal_update_sb_log_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2480)
Location: fs/jbd2/journal.c:1381
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff812f2480-ffffffff812f2507: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131fe80)
Location: fs/jbd2/journal.c:1409
Inline: True
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8131fe80-ffffffff8131ff07: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335d40)
Location: fs/jbd2/journal.c:1378
Inline: True
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81335d40-ffffffff81335dcc: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134aa90)
Location: fs/jbd2/journal.c:1401
Inline: True
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8134aa90-ffffffff8134ab0a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136f0e0)
Location: fs/jbd2/journal.c:1417
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8136f0e0-ffffffff8136f15a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139d690)
Location: fs/jbd2/journal.c:1414
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8139d690-ffffffff8139d716: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b6400)
Location: fs/jbd2/journal.c:1414
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813b6400-ffffffff813b6486: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1405
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813e19b4-ffffffff813e19c7: jbd2_journal_update_sb_log_tail.cold (STB_LOCAL)
ffffffff813e0b30-ffffffff813e0be9: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fab70)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813fab70-ffffffff813fac2a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81448310)
Location: fs/jbd2/journal.c:1425
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:__jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81448310-ffffffff814483ca: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464e50)
Location: fs/jbd2/journal.c:1613
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:__jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81464e50-ffffffff81464f0a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a5e0)
Location: fs/jbd2/journal.c:1613
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:__jbd2_update_log_tail
```
**Symbols:**

```
ffffffff8146a5e0-ffffffff8146a69a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0d40)
Location: fs/jbd2/journal.c:1661
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
```
**Symbols:**

```
ffffffff814c0d40-ffffffff814c0e1c: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154b5f0)
Location: fs/jbd2/journal.c:1667
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
```
**Symbols:**

```
ffffffff8154b5f0-ffffffff8154b6ce: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, blk_opf_t write_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eb2d0)
Location: fs/jbd2/journal.c:1672
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
```
**Symbols:**

```
ffffffff815eb2d0-ffffffff815eb3ae: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, blk_opf_t write_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81622d40)
Location: fs/jbd2/journal.c:1685
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
```
**Symbols:**

```
ffffffff81622d40-ffffffff81622e1e: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, blk_opf_t write_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165bda0)
Location: fs/jbd2/journal.c:1856
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:journal_reset
```
**Symbols:**

```
ffffffff8165bda0-ffffffff8165be9e: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
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
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d7f30)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffff8000104d7f30-ffff8000104d8098: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699dd8)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c0699dd8-c0699f28: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000612c50)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c000000000612c50-c000000000612d98: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034db10)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffe00034db10-ffffffe00034dc16: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
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
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3150)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813f3150-ffffffff813f320a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e3bd0)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813e3bd0-ffffffff813e3c8a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f04d0)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff813f04d0-ffffffff813f058a: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_update_sb_log_tail(journal_t *journal, tid_t tail_tid, long unsigned int tail_block, int write_op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405f20)
Location: fs/jbd2/journal.c:1404
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81405f20-ffffffff81405fd8: jbd2_journal_update_sb_log_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t write_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write_op</code>
</li>
</ul>
</details>
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
