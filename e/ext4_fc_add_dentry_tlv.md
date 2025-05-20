# Function: <code>ext4_fc_add_dentry_tlv</code>

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
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u16 tag, int parent_ino, int ino, int dlen, const unsigned char *dname, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454d40)
Location: fs/ext4/fast_commit.c:778
Inline: False
```
**Symbols:**

```
ffffffff81454d40-ffffffff81454e19: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u16 tag, int parent_ino, int ino, int dlen, const unsigned char *dname, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145a460)
Location: fs/ext4/fast_commit.c:778
Inline: False
```
**Symbols:**

```
ffffffff8145a460-ffffffff8145a539: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u32 *crc, struct ext4_fc_dentry_update *fc_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ae2e0)
Location: fs/ext4/fast_commit.c:746
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff814ae2e0-ffffffff814ae3ac: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u32 *crc, struct ext4_fc_dentry_update *fc_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536a00)
Location: fs/ext4/fast_commit.c:825
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81536a00-ffffffff81536aea: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u32 *crc, struct ext4_fc_dentry_update *fc_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4dc0)
Location: fs/ext4/fast_commit.c:816
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff815d4dc0-ffffffff815d4e5b: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u32 *crc, struct ext4_fc_dentry_update *fc_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160c9b0)
Location: fs/ext4/fast_commit.c:816
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8160c9b0-ffffffff8160ca27: ext4_fc_add_dentry_tlv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_fc_add_dentry_tlv(struct super_block *sb, u32 *crc, struct ext4_fc_dentry_update *fc_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81645770)
Location: fs/ext4/fast_commit.c:816
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81645770-ffffffff816457e7: ext4_fc_add_dentry_tlv (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_fc_dentry_update *fc_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>u16 tag</code>
</li>
<li>
<b>Param removed. </b>
<code>int parent_ino</code>
</li>
<li>
<b>Param removed. </b>
<code>int ino</code>
</li>
<li>
<b>Param removed. </b>
<code>int dlen</code>
</li>
<li>
<b>Param removed. </b>
<code>const unsigned char *dname</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, tag, parent_ino, ino, dlen, dname, crc</code> ➡️ <code>sb, crc, fc_dentry</code>
</li>
</ul>
</details>
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
