# Function: <code>jbd2_fc_release_bufs</code>

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
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81460530)
Location: fs/jbd2/journal.c:941
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff81460530-ffffffff8146058d: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81465ce0)
Location: fs/jbd2/journal.c:941
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff81465ce0-ffffffff81465d3d: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bb7d0)
Location: fs/jbd2/journal.c:937
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff814bb7d0-ffffffff814bb82d: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81545870)
Location: fs/jbd2/journal.c:939
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff81545870-ffffffff815458d7: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e4b50)
Location: fs/jbd2/journal.c:942
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff815e4b50-ffffffff815e4bb7: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161c4b0)
Location: fs/jbd2/journal.c:941
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff8161c4b0-ffffffff8161c517: jbd2_fc_release_bufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_fc_release_bufs(journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816553c0)
Location: fs/jbd2/journal.c:930
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
**Symbols:**

```
ffffffff816553c0-ffffffff81655427: jbd2_fc_release_bufs (STB_GLOBAL)
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
