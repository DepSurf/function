# Function: <code>jbd2_fc_end_commit_fallback</code>

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
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464940)
Location: fs/jbd2/journal.c:790
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81464940-ffffffff81464985: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a0d0)
Location: fs/jbd2/journal.c:790
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8146a0d0-ffffffff8146a115: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0460)
Location: fs/jbd2/journal.c:790
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff814c0460-ffffffff814c04a5: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154ace0)
Location: fs/jbd2/journal.c:792
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8154ace0-ffffffff8154ad36: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9ba0)
Location: fs/jbd2/journal.c:789
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff815e9ba0-ffffffff815e9bf6: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621990)
Location: fs/jbd2/journal.c:788
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81621990-ffffffff816219e6: jbd2_fc_end_commit_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_fc_end_commit_fallback(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659eb0)
Location: fs/jbd2/journal.c:777
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81659eb0-ffffffff81659f06: jbd2_fc_end_commit_fallback (STB_GLOBAL)
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
