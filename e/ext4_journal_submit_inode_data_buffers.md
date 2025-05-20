# Function: <code>ext4_journal_submit_inode_data_buffers</code>

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
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cfe0)
Location: fs/ext4/super.c:526
Inline: False
```
**Symbols:**

```
ffffffff8143cfe0-ffffffff8143d087: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442e30)
Location: fs/ext4/super.c:526
Inline: False
```
**Symbols:**

```
ffffffff81442e30-ffffffff81442ed7: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496ad0)
Location: fs/ext4/super.c:523
Inline: False
```
**Symbols:**

```
ffffffff81496ad0-ffffffff81496b77: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521a70)
Location: fs/ext4/super.c:542
Inline: False
```
**Symbols:**

```
ffffffff81521a70-ffffffff81521aaf: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bed70)
Location: fs/ext4/super.c:536
Inline: False
```
**Symbols:**

```
ffffffff815bed70-ffffffff815bedaf: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f5b10)
Location: fs/ext4/super.c:536
Inline: False
```
**Symbols:**

```
ffffffff815f5b10-ffffffff815f5b4f: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_journal_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162e420)
Location: fs/ext4/super.c:596
Inline: False
```
**Symbols:**

```
ffffffff8162e420-ffffffff8162e45f: ext4_journal_submit_inode_data_buffers (STB_LOCAL)
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
