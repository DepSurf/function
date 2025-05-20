# Function: <code>__jbd2_fc_end_commit</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464995)
Location: fs/jbd2/journal.c:769
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
```
**Symbols:**

```
ffffffff814648b0-ffffffff81464938: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a125)
Location: fs/jbd2/journal.c:769
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
```
**Symbols:**

```
ffffffff8146a040-ffffffff8146a0c8: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c04b5)
Location: fs/jbd2/journal.c:769
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
```
**Symbols:**

```
ffffffff814c03d0-ffffffff814c045a: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154abe0)
Location: fs/jbd2/journal.c:770
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff8154abe0-ffffffff8154acb3: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9a80)
Location: fs/jbd2/journal.c:767
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff815e9a80-ffffffff815e9b53: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621880)
Location: fs/jbd2/journal.c:766
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff81621880-ffffffff8162194e: __jbd2_fc_end_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __jbd2_fc_end_commit(journal_t *journal, tid_t tid, bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659da0)
Location: fs/jbd2/journal.c:755
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_fc_end_commit_fallback
  - fs/jbd2/journal.c:jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff81659da0-ffffffff81659e6e: __jbd2_fc_end_commit (STB_LOCAL)
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
