# Function: <code>jbd2_fc_begin_commit</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81461b90)
Location: fs/jbd2/journal.c:730
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81461b90-ffffffff81461c91: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467240)
Location: fs/jbd2/journal.c:730
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81467240-ffffffff81467341: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bd1e0)
Location: fs/jbd2/journal.c:730
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff814bd1e0-ffffffff814bd2e1: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815484e0)
Location: fs/jbd2/journal.c:730
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff815484e0-ffffffff81548604: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e7be0)
Location: fs/jbd2/journal.c:727
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff815e7be0-ffffffff815e7d04: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161f4f0)
Location: fs/jbd2/journal.c:726
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8161f4f0-ffffffff8161f614: jbd2_fc_begin_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_fc_begin_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81658400)
Location: fs/jbd2/journal.c:715
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81658400-ffffffff81658524: jbd2_fc_begin_commit (STB_GLOBAL)
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
