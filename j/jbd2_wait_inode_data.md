# Function: <code>jbd2_wait_inode_data</code>

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
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8145ba10)
Location: fs/jbd2/commit.c:222
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8145ba10-ffffffff8145ba49: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81461350)
Location: fs/jbd2/commit.c:222
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81461350-ffffffff81461389: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff814b6840)
Location: fs/jbd2/commit.c:222
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff814b6840-ffffffff814b6879: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81540250)
Location: fs/jbd2/commit.c:224
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81540250-ffffffff815402a7: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff815deda0)
Location: fs/jbd2/commit.c:221
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff815deda0-ffffffff815dedf7: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff81616800)
Location: fs/jbd2/commit.c:192
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81616800-ffffffff81616857: jbd2_wait_inode_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_wait_inode_data(journal_t *journal, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/commit.c (ffffffff8164f620)
Location: fs/jbd2/commit.c:192
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8164f620-ffffffff8164f677: jbd2_wait_inode_data (STB_GLOBAL)
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
