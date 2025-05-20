# Function: <code>ext4_journal_finish_inode_data_buffers</code>

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
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cfa0)
Location: fs/ext4/super.c:538
Inline: False
```
**Symbols:**

```
ffffffff8143cfa0-ffffffff8143cfd6: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442df0)
Location: fs/ext4/super.c:538
Inline: False
```
**Symbols:**

```
ffffffff81442df0-ffffffff81442e26: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496a90)
Location: fs/ext4/super.c:535
Inline: False
```
**Symbols:**

```
ffffffff81496a90-ffffffff81496ac6: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521980)
Location: fs/ext4/super.c:554
Inline: False
```
**Symbols:**

```
ffffffff81521980-ffffffff815219c3: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bec60)
Location: fs/ext4/super.c:547
Inline: False
```
**Symbols:**

```
ffffffff815bec60-ffffffff815beca3: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f5a00)
Location: fs/ext4/super.c:547
Inline: False
```
**Symbols:**

```
ffffffff815f5a00-ffffffff815f5a43: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_journal_finish_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162e310)
Location: fs/ext4/super.c:607
Inline: False
```
**Symbols:**

```
ffffffff8162e310-ffffffff8162e353: ext4_journal_finish_inode_data_buffers (STB_LOCAL)
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
