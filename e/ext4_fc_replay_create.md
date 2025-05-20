# Function: <code>ext4_fc_replay_create</code>

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
int ext4_fc_replay_create(struct super_block *sb, struct ext4_fc_tl *tl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814544f0)
Location: fs/ext4/fast_commit.c:1555
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814544f0-ffffffff8145466d: ext4_fc_replay_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_replay_create(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81459cd0)
Location: fs/ext4/fast_commit.c:1554
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81459cd0-ffffffff81459e54: ext4_fc_replay_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_replay_create(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ae500)
Location: fs/ext4/fast_commit.c:1532
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814ae500-ffffffff814ae681: ext4_fc_replay_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_replay_create(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815372d0)
Location: fs/ext4/fast_commit.c:1613
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815372d0-ffffffff815374b2: ext4_fc_replay_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d7859)
Location: fs/ext4/fast_commit.c:1620
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160f436)
Location: fs/ext4/fast_commit.c:1620
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816481f6)
Location: fs/ext4/fast_commit.c:1620
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *val</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
