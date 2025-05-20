# Function: <code>jbd2_journal_shrink_checkpoint_list</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t *journal, long unsigned int *nr_to_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:505
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
**Symbols:**

```
ffffffff81cce87c-ffffffff81cce897: jbd2_journal_shrink_checkpoint_list.cold (STB_LOCAL)
ffffffff814ba260-ffffffff814ba471: jbd2_journal_shrink_checkpoint_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t *journal, long unsigned int *nr_to_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:505
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
**Symbols:**

```
ffffffff81e8191d-ffffffff81e81938: jbd2_journal_shrink_checkpoint_list.cold (STB_LOCAL)
ffffffff81544020-ffffffff815442ac: jbd2_journal_shrink_checkpoint_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t *journal, long unsigned int *nr_to_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/checkpoint.c (0)
Location: fs/jbd2/checkpoint.c:505
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
**Symbols:**

```
ffffffff82071396-ffffffff820713b1: jbd2_journal_shrink_checkpoint_list.cold (STB_LOCAL)
ffffffff815e3000-ffffffff815e328c: jbd2_journal_shrink_checkpoint_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t *journal, long unsigned int *nr_to_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8161a8e0)
Location: fs/jbd2/checkpoint.c:409
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
**Symbols:**

```
ffffffff8161a8e0-ffffffff8161aadd: jbd2_journal_shrink_checkpoint_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t *journal, long unsigned int *nr_to_scan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81653800)
Location: fs/jbd2/checkpoint.c:403
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
**Symbols:**

```
ffffffff81653800-ffffffff81653a00: jbd2_journal_shrink_checkpoint_list (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
