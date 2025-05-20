# Function: <code>jbd2_transaction_committed</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136ae80)
Location: fs/jbd2/journal.c:741
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8136ae80-ffffffff8136aed6: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81399630)
Location: fs/jbd2/journal.c:738
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81399630-ffffffff81399686: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b23a0)
Location: fs/jbd2/journal.c:738
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813b23a0-ffffffff813b23f6: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813dca10)
Location: fs/jbd2/journal.c:721
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813dca10-ffffffff813dca66: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f6a50)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813f6a50-ffffffff813f6aa6: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81446000)
Location: fs/jbd2/journal.c:718
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff81446000-ffffffff81446056: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81462430)
Location: fs/jbd2/journal.c:803
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff81462430-ffffffff81462486: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467ae0)
Location: fs/jbd2/journal.c:803
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff81467ae0-ffffffff81467b36: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bdf40)
Location: fs/jbd2/journal.c:803
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff814bdf40-ffffffff814bdf99: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815457f0)
Location: fs/jbd2/journal.c:805
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff815457f0-ffffffff81545861: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e4ac0)
Location: fs/jbd2/journal.c:802
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff815e4ac0-ffffffff815e4b31: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161c420)
Location: fs/jbd2/journal.c:801
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff8161c420-ffffffff8161c491: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81655340)
Location: fs/jbd2/journal.c:790
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_set_iomap
```
**Symbols:**

```
ffffffff81655340-ffffffff816553ae: jbd2_transaction_committed (STB_GLOBAL)
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
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d4e60)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffff8000104d4e60-ffff8000104d4f30: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0698850)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c0698850-c06988dc: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c00000000060c5f0)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c00000000060c5f0-c00000000060c6d4: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe000349b86)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffe000349b86-ffffffe000349be4: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ef030)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813ef030-ffffffff813ef086: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813dfab0)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813dfab0-ffffffff813dfb06: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ec3b0)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813ec3b0-ffffffff813ec406: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_transaction_committed(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81401d50)
Location: fs/jbd2/journal.c:719
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81401d50-ffffffff81401db6: jbd2_transaction_committed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
