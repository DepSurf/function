# Function: <code>jbd2_write_superblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1900)
Location: fs/jbd2/journal.c:1326
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff812f1900-ffffffff812f1ac2: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f110)
Location: fs/jbd2/journal.c:1354
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
**Symbols:**

```
ffffffff8131f110-ffffffff8131f35b: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335190)
Location: fs/jbd2/journal.c:1323
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
**Symbols:**

```
ffffffff81335190-ffffffff813353dd: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81349f30)
Location: fs/jbd2/journal.c:1346
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
**Symbols:**

```
ffffffff81349f30-ffffffff8134a15c: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e580)
Location: fs/jbd2/journal.c:1362
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff8136e580-ffffffff8136e7af: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1359
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff8139cbe0-ffffffff8139cde4: jbd2_write_superblock (STB_LOCAL)
ffffffff8139e3f0-ffffffff8139e428: jbd2_write_superblock.cold.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1359
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813b5950-ffffffff813b5b54: jbd2_write_superblock (STB_LOCAL)
ffffffff813b7160-ffffffff813b7198: jbd2_write_superblock.cold.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1346
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813e0040-ffffffff813e0245: jbd2_write_superblock (STB_LOCAL)
ffffffff813e18d8-ffffffff813e1910: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813fa080-ffffffff813fa285: jbd2_write_superblock (STB_LOCAL)
ffffffff813fb928-ffffffff813fb960: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1363
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff81447640-ffffffff81447855: jbd2_write_superblock (STB_LOCAL)
ffffffff81449084-ffffffff814490d3: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1551
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff81463fd0-ffffffff814641d4: jbd2_write_superblock (STB_LOCAL)
ffffffff81bed1d1-ffffffff81bed221: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1551
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff81469680-ffffffff81469884: jbd2_write_superblock (STB_LOCAL)
ffffffff81bdf2b5-ffffffff81bdf305: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1599
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff814bfb20-ffffffff814bfd24: jbd2_write_superblock (STB_LOCAL)
ffffffff81ccebed-ffffffff81ccec3d: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1605
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff8154a2b0-ffffffff8154a4ce: jbd2_write_superblock (STB_LOCAL)
ffffffff81e81c6e-ffffffff81e81ca3: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9c10)
Location: fs/jbd2/journal.c:1611
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff815e9c10-ffffffff815e9e44: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621a00)
Location: fs/jbd2/journal.c:1624
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff81621a00-ffffffff81621c30: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659f20)
Location: fs/jbd2/journal.c:1788
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff81659f20-ffffffff8165a165: jbd2_write_superblock (STB_LOCAL)
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
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d6ef8)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffff8000104d6ef8-ffff8000104d7108: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699030)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
c0699030-c0699288: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000611a20)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
c000000000611a20-c000000000611d30: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034ceb2)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffe00034ceb2-ffffffe00034d072: jbd2_write_superblock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813f2660-ffffffff813f2865: jbd2_write_superblock (STB_LOCAL)
ffffffff813f3f08-ffffffff813f3f40: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813e30e0-ffffffff813e32e5: jbd2_write_superblock (STB_LOCAL)
ffffffff813e4988-ffffffff813e49c0: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff813ef9e0-ffffffff813efbe5: jbd2_write_superblock (STB_LOCAL)
ffffffff813f1288-ffffffff813f12c0: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int jbd2_write_superblock(journal_t *journal, int write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1345
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
**Symbols:**

```
ffffffff814053f0-ffffffff81405609: jbd2_write_superblock (STB_LOCAL)
ffffffff81406e93-ffffffff81406ecb: jbd2_write_superblock.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int write_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write_op</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>int write_flags</code> ➡️ <code>blk_opf_t write_flags</code>
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
