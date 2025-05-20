# Function: <code>jbd2_journal_submit_inode_data_buffers</code>

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
int jbd2_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8145bf11)
Location: fs/jbd2/commit.c:190
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff8145c210-ffffffff8145c287: jbd2_journal_submit_inode_data_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81461501)
Location: fs/jbd2/commit.c:190
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff81461880-ffffffff814618f7: jbd2_journal_submit_inode_data_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int jbd2_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff814b6bde)
Location: fs/jbd2/commit.c:190
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff814b6d70-ffffffff814b6dea: jbd2_journal_submit_inode_data_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81540700)
Location: fs/jbd2/commit.c:192
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff81540700-ffffffff81540789: jbd2_journal_submit_inode_data_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff815df370)
Location: fs/jbd2/commit.c:190
Inline: False
```
**Symbols:**

```
ffffffff815df370-ffffffff815df3f9: jbd2_journal_submit_inode_data_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
