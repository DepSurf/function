# Function: <code>jbd2_mark_journal_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1b20)
Location: fs/jbd2/journal.c:1415
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff812f1b20-ffffffff812f1bac: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131f3b0)
Location: fs/jbd2/journal.c:1444
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8131f3b0-ffffffff8131f443: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335430)
Location: fs/jbd2/journal.c:1413
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81335430-ffffffff813354c7: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a1b0)
Location: fs/jbd2/journal.c:1436
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8134a1b0-ffffffff8134a247: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e800)
Location: fs/jbd2/journal.c:1452
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8136e800-ffffffff8136e897: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139ce40)
Location: fs/jbd2/journal.c:1452
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8139ce40-ffffffff8139ced7: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b5bb0)
Location: fs/jbd2/journal.c:1452
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813b5bb0-ffffffff813b5c47: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e02b0)
Location: fs/jbd2/journal.c:1444
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813e02b0-ffffffff813e034a: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fa2f0)
Location: fs/jbd2/journal.c:1443
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813fa2f0-ffffffff813fa38b: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814478c0)
Location: fs/jbd2/journal.c:1464
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff814478c0-ffffffff8144795b: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464240)
Location: fs/jbd2/journal.c:1652
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81464240-ffffffff81464319: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814698f0)
Location: fs/jbd2/journal.c:1652
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff814698f0-ffffffff814699c9: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bfd90)
Location: fs/jbd2/journal.c:1704
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff814bfd90-ffffffff814bfe69: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154a540)
Location: fs/jbd2/journal.c:1710
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8154a540-ffffffff8154a644: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9fb0)
Location: fs/jbd2/journal.c:1716
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff815e9fb0-ffffffff815ea0b4: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621d90)
Location: fs/jbd2/journal.c:1729
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81621d90-ffffffff81621eab: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, blk_opf_t write_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165a2d0)
Location: fs/jbd2/journal.c:1900
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff8165a2d0-ffffffff8165a3eb: jbd2_mark_journal_empty (STB_LOCAL)
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
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d71b8)
Location: fs/jbd2/journal.c:1443
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffff8000104d71b8-ffff8000104d72fc: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699344)
Location: fs/jbd2/journal.c:1443
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
c0699344-c0699460: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000611df0)
Location: fs/jbd2/journal.c:1443
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
c000000000611df0-c000000000611f20: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d108)
Location: fs/jbd2/journal.c:1443
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffe00034d108-ffffffe00034d1e4: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f28d0)
Location: fs/jbd2/journal.c:1443
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813f28d0-ffffffff813f296b: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e3350)
Location: fs/jbd2/journal.c:1443
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813e3350-ffffffff813e33eb: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813efc50)
Location: fs/jbd2/journal.c:1443
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff813efc50-ffffffff813efceb: jbd2_mark_journal_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void jbd2_mark_journal_empty(journal_t *journal, int write_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405660)
Location: fs/jbd2/journal.c:1443
Inline: True
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
**Symbols:**

```
ffffffff81405660-ffffffff814056f3: jbd2_mark_journal_empty (STB_LOCAL)
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
