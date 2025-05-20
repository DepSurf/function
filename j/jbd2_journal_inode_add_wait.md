# Function: <code>jbd2_journal_inode_add_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813172b0)
Location: fs/jbd2/transaction.c:2534
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813172b0-ffffffff813172c5: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132d2a0)
Location: fs/jbd2/transaction.c:2539
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8132d2a0-ffffffff8132d2b5: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81342470)
Location: fs/jbd2/transaction.c:2557
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81342470-ffffffff81342485: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81366aa0)
Location: fs/jbd2/transaction.c:2560
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81366aa0-ffffffff81366ab5: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81395190)
Location: fs/jbd2/transaction.c:2563
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81395190-ffffffff813951a5: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813adf00)
Location: fs/jbd2/transaction.c:2603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813adf00-ffffffff813adf15: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_inode_add_wait(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d8280)
Location: fs/jbd2/transaction.c:2628
Inline: False
```
**Symbols:**

```
ffffffff813d8280-ffffffff813d82a1: jbd2_journal_inode_add_wait (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
