# Function: <code>squashfs_bio_read</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff81449280)
Location: fs/squashfs/block.c:76
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81449280-ffffffff81449462: squashfs_bio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff814659f0)
Location: fs/squashfs/block.c:76
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff814659f0-ffffffff81465bd5: squashfs_bio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8146b1a0)
Location: fs/squashfs/block.c:76
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8146b1a0-ffffffff8146b386: squashfs_bio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:75
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff814c19e0-ffffffff814c1bdb: squashfs_bio_read (STB_LOCAL)
ffffffff81ccee0d-ffffffff81cceeb9: squashfs_bio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:75
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8154c410-ffffffff8154c5e8: squashfs_bio_read (STB_LOCAL)
ffffffff81e81e5a-ffffffff81e81f0e: squashfs_bio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:79
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff815ec250-ffffffff815ec428: squashfs_bio_read (STB_LOCAL)
ffffffff82071467-ffffffff8207151b: squashfs_bio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:189
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81624020-ffffffff81624384: squashfs_bio_read (STB_LOCAL)
ffffffff820f112c-ffffffff820f11cb: squashfs_bio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int squashfs_bio_read(struct super_block *sb, u64 index, int length, struct bio **biop, int *block_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/block.c (0)
Location: fs/squashfs/block.c:189
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8165d0c0-ffffffff8165d41e: squashfs_bio_read (STB_LOCAL)
ffffffff821ce3d4-ffffffff821ce473: squashfs_bio_read.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
