# Function: <code>ext4_fc_memcpy</code>

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
void *ext4_fc_memcpy(struct super_block *sb, void *dst, const void *src, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81455622)
Location: fs/ext4/fast_commit.c:703
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
```
**Symbols:**

```
ffffffff81454300-ffffffff8145439c: ext4_fc_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *ext4_fc_memcpy(struct super_block *sb, void *dst, const void *src, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145bf7c)
Location: fs/ext4/fast_commit.c:703
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff81459c30-ffffffff81459ccc: ext4_fc_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *ext4_fc_memcpy(struct super_block *sb, void *dst, const void *src, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814af7af)
Location: fs/ext4/fast_commit.c:671
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff814adde0-ffffffff814ade7c: ext4_fc_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ext4_fc_memcpy(struct super_block *sb, void *dst, const void *src, int len, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536440)
Location: fs/ext4/fast_commit.c:750
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_dentry_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
  - fs/ext4/fast_commit.c:ext4_fc_add_tlv
```
**Symbols:**

```
ffffffff81536440-ffffffff815364fb: ext4_fc_memcpy (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
