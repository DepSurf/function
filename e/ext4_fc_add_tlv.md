# Function: <code>ext4_fc_add_tlv</code>

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
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454af0)
Location: fs/ext4/fast_commit.c:758
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff81454af0-ffffffff81454b9e: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145a220)
Location: fs/ext4/fast_commit.c:758
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff8145a220-ffffffff8145a2ce: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ae0a0)
Location: fs/ext4/fast_commit.c:726
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff814ae0a0-ffffffff814ae14e: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536750)
Location: fs/ext4/fast_commit.c:805
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff81536750-ffffffff81536813: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4b00)
Location: fs/ext4/fast_commit.c:796
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff815d4b00-ffffffff815d4bb3: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160c6f0)
Location: fs/ext4/fast_commit.c:796
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff8160c6f0-ffffffff8160c7a3: ext4_fc_add_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_fc_add_tlv(struct super_block *sb, u16 tag, u16 len, u8 *val, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816454b0)
Location: fs/ext4/fast_commit.c:796
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
**Symbols:**

```
ffffffff816454b0-ffffffff81645563: ext4_fc_add_tlv (STB_LOCAL)
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
