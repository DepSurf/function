# Function: <code>ext4_journalled_submit_inode_data_buffers</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143d00e)
Location: fs/ext4/super.c:511
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
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
In fs/ext4/super.c (ffffffff81442e5e)
Location: fs/ext4/super.c:511
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
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
In fs/ext4/super.c (ffffffff81496afe)
Location: fs/ext4/super.c:508
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_journalled_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815219d0)
Location: fs/ext4/super.c:527
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff815219d0-ffffffff81521a63: ext4_journalled_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_journalled_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815becc0)
Location: fs/ext4/super.c:521
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff815becc0-ffffffff815bed53: ext4_journalled_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_journalled_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f5a60)
Location: fs/ext4/super.c:521
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff815f5a60-ffffffff815f5af3: ext4_journalled_submit_inode_data_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_journalled_submit_inode_data_buffers(struct jbd2_inode *jinode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162e370)
Location: fs/ext4/super.c:581
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_submit_inode_data_buffers
```
**Symbols:**

```
ffffffff8162e370-ffffffff8162e403: ext4_journalled_submit_inode_data_buffers (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
