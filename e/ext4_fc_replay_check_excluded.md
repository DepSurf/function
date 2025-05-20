# Function: <code>ext4_fc_replay_check_excluded</code>

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
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81457430)
Location: fs/ext4/fast_commit.c:1881
Inline: False
```
**Symbols:**

```
ffffffff81457430-ffffffff81457497: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145cdc0)
Location: fs/ext4/fast_commit.c:1881
Inline: False
```
**Symbols:**

```
ffffffff8145cdc0-ffffffff8145ce24: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0e30)
Location: fs/ext4/fast_commit.c:1864
Inline: False
```
**Symbols:**

```
ffffffff814b0e30-ffffffff814b0e94: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815398b0)
Location: fs/ext4/fast_commit.c:1948
Inline: False
```
**Symbols:**

```
ffffffff815398b0-ffffffff8153992b: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d7d90)
Location: fs/ext4/fast_commit.c:1956
Inline: False
```
**Symbols:**

```
ffffffff815d7d90-ffffffff815d7e0b: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160f920)
Location: fs/ext4/fast_commit.c:1956
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
```
**Symbols:**

```
ffffffff8160f920-ffffffff8160f99b: ext4_fc_replay_check_excluded (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_fc_replay_check_excluded(struct super_block *sb, ext4_fsblk_t blk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816486e0)
Location: fs/ext4/fast_commit.c:1956
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
```
**Symbols:**

```
ffffffff816486e0-ffffffff81648754: ext4_fc_replay_check_excluded (STB_GLOBAL)
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
