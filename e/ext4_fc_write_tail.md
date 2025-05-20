# Function: <code>ext4_fc_write_tail</code>

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
int ext4_fc_write_tail(struct super_block *sb, u32 crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81455540)
Location: fs/ext4/fast_commit.c:719
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81455540-ffffffff81455651: ext4_fc_write_tail (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff8145bec5)
Location: fs/ext4/fast_commit.c:719
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
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
In fs/ext4/fast_commit.c (ffffffff814af6f5)
Location: fs/ext4/fast_commit.c:687
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81537172)
Location: fs/ext4/fast_commit.c:766
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_write_tail(struct super_block *sb, u32 crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4e70)
Location: fs/ext4/fast_commit.c:753
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff815d4e70-ffffffff815d4fbb: ext4_fc_write_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_write_tail(struct super_block *sb, u32 crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160ca40)
Location: fs/ext4/fast_commit.c:753
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff8160ca40-ffffffff8160cb8b: ext4_fc_write_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_write_tail(struct super_block *sb, u32 crc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81645800)
Location: fs/ext4/fast_commit.c:753
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81645800-ffffffff8164594b: ext4_fc_write_tail (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
