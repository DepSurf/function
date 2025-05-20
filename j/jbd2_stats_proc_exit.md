# Function: <code>jbd2_stats_proc_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jbd2_stats_proc_exit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812eefe0)
Location: fs/jbd2/journal.c:1054
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_init_inode
```
**Symbols:**

```
ffffffff812eefe0-ffffffff812ef016: jbd2_stats_proc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_stats_proc_exit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131d560)
Location: fs/jbd2/journal.c:1078
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff8131d560-ffffffff8131d596: jbd2_stats_proc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81335669)
Location: fs/jbd2/journal.c:1078
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134a3f1)
Location: fs/jbd2/journal.c:1101
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136ea41)
Location: fs/jbd2/journal.c:1117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139d07d)
Location: fs/jbd2/journal.c:1114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b5ded)
Location: fs/jbd2/journal.c:1114
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e050b)
Location: fs/jbd2/journal.c:1097
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fa54b)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81447a61)
Location: fs/jbd2/journal.c:1099
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464421)
Location: fs/jbd2/journal.c:1278
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81469b94)
Location: fs/jbd2/journal.c:1278
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0096)
Location: fs/jbd2/journal.c:1270
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154a89c)
Location: fs/jbd2/journal.c:1272
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815ea39c)
Location: fs/jbd2/journal.c:1275
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8162218c)
Location: fs/jbd2/journal.c:1277
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165a6cc)
Location: fs/jbd2/journal.c:1265
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d7574)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0699670)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0000000006121d8)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034d3b2)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f2b2b)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e35ab)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813efeab)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814058b0)
Location: fs/jbd2/journal.c:1096
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
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
</ul>
