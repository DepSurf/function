# Function: <code>jbd2_journal_wait_updates</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jbd2_journal_wait_updates(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153e350)
Location: fs/jbd2/transaction.c:835
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8153e350-ffffffff8153e433: jbd2_journal_wait_updates (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jbd2_journal_wait_updates(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dcc70)
Location: fs/jbd2/transaction.c:835
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff815dcc70-ffffffff815dcd53: jbd2_journal_wait_updates (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jbd2_journal_wait_updates(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81614710)
Location: fs/jbd2/transaction.c:835
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81614710-ffffffff816147f3: jbd2_journal_wait_updates (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jbd2_journal_wait_updates(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164d500)
Location: fs/jbd2/transaction.c:835
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8164d500-ffffffff8164d5e3: jbd2_journal_wait_updates (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
