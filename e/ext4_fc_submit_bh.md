# Function: <code>ext4_fc_submit_bh</code>

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
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454250)
Location: fs/ext4/fast_commit.c:612
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff81454250-ffffffff814542fc: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81459b80)
Location: fs/ext4/fast_commit.c:612
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff81459b80-ffffffff81459c2c: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814adc70)
Location: fs/ext4/fast_commit.c:580
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff814adc70-ffffffff814add1c: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81535b60)
Location: fs/ext4/fast_commit.c:659
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff81535b60-ffffffff81535bfa: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4010)
Location: fs/ext4/fast_commit.c:660
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff815d4010-ffffffff815d40aa: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160bbf0)
Location: fs/ext4/fast_commit.c:660
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff8160bbf0-ffffffff8160bc8a: ext4_fc_submit_bh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block *sb, bool is_tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816449b0)
Location: fs/ext4/fast_commit.c:660
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff816449b0-ffffffff81644a4a: ext4_fc_submit_bh (STB_LOCAL)
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
