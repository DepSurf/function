# Function: <code>ext4_fc_write_inode</code>

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
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454e20)
Location: fs/ext4/fast_commit.c:809
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81454e20-ffffffff81454f64: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145a540)
Location: fs/ext4/fast_commit.c:809
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8145a540-ffffffff8145a684: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ae3b0)
Location: fs/ext4/fast_commit.c:776
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff814ae3b0-ffffffff814ae4f4: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536af0)
Location: fs/ext4/fast_commit.c:854
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81536af0-ffffffff81536c8c: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4fd0)
Location: fs/ext4/fast_commit.c:845
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff815d4fd0-ffffffff815d5116: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160cba0)
Location: fs/ext4/fast_commit.c:845
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8160cba0-ffffffff8160ccdf: ext4_fc_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_write_inode(struct inode *inode, u32 *crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81645960)
Location: fs/ext4/fast_commit.c:845
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81645960-ffffffff81645a9f: ext4_fc_write_inode (STB_LOCAL)
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
