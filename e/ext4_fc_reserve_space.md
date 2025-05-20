# Function: <code>ext4_fc_reserve_space</code>

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
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814548d0)
Location: fs/ext4/fast_commit.c:653
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
```
**Symbols:**

```
ffffffff814548d0-ffffffff81454aea: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145a000)
Location: fs/ext4/fast_commit.c:653
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff8145a000-ffffffff8145a21e: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ade80)
Location: fs/ext4/fast_commit.c:621
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff814ade80-ffffffff814ae09e: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536500)
Location: fs/ext4/fast_commit.c:700
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff81536500-ffffffff8153674f: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4950)
Location: fs/ext4/fast_commit.c:689
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
```
**Symbols:**

```
ffffffff815d4950-ffffffff815d4aec: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160c540)
Location: fs/ext4/fast_commit.c:689
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
```
**Symbols:**

```
ffffffff8160c540-ffffffff8160c6dc: ext4_fc_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 *ext4_fc_reserve_space(struct super_block *sb, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81645300)
Location: fs/ext4/fast_commit.c:689
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
```
**Symbols:**

```
ffffffff81645300-ffffffff8164549c: ext4_fc_reserve_space (STB_LOCAL)
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
