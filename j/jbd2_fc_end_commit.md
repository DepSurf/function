# Function: <code>jbd2_fc_end_commit</code>

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
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464990)
Location: fs/jbd2/journal.c:784
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81464990-ffffffff814649e4: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a120)
Location: fs/jbd2/journal.c:784
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8146a120-ffffffff8146a174: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c04b0)
Location: fs/jbd2/journal.c:784
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff814c04b0-ffffffff814c0506: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154acc0)
Location: fs/jbd2/journal.c:786
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8154acc0-ffffffff8154acde: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9b70)
Location: fs/jbd2/journal.c:783
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff815e9b70-ffffffff815e9b8e: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621960)
Location: fs/jbd2/journal.c:782
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81621960-ffffffff8162197e: jbd2_fc_end_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_fc_end_commit(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659e80)
Location: fs/jbd2/journal.c:771
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81659e80-ffffffff81659e9e: jbd2_fc_end_commit (STB_GLOBAL)
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
