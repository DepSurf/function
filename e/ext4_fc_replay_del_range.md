# Function: <code>ext4_fc_replay_del_range</code>

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
int ext4_fc_replay_del_range(struct super_block *sb, struct ext4_fc_tl *tl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454670)
Location: fs/ext4/fast_commit.c:1770
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81454670-ffffffff814547ec: ext4_fc_replay_del_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81459e60)
Location: fs/ext4/fast_commit.c:1769
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81459e60-ffffffff81459ff4: ext4_fc_replay_del_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (0)
Location: fs/ext4/fast_commit.c:1750
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814ae690-ffffffff814ae83a: ext4_fc_replay_del_range.constprop.0 (STB_LOCAL)
ffffffff81cce29a-ffffffff81cce2bd: ext4_fc_replay_del_range.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (0)
Location: fs/ext4/fast_commit.c:1830
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815374c0-ffffffff815376af: ext4_fc_replay_del_range.constprop.0 (STB_LOCAL)
ffffffff81e812c1-ffffffff81e812e4: ext4_fc_replay_del_range.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (0)
Location: fs/ext4/fast_commit.c:1839
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815d5680-ffffffff815d586f: ext4_fc_replay_del_range.constprop.0 (STB_LOCAL)
ffffffff8207118d-ffffffff820711b0: ext4_fc_replay_del_range.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (0)
Location: fs/ext4/fast_commit.c:1839
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff8160d240-ffffffff8160d42e: ext4_fc_replay_del_range.isra.0 (STB_LOCAL)
ffffffff820f0e73-ffffffff820f0e96: ext4_fc_replay_del_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (0)
Location: fs/ext4/fast_commit.c:1839
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81646000-ffffffff816461ee: ext4_fc_replay_del_range.isra.0 (STB_LOCAL)
ffffffff821ce02a-ffffffff821ce04d: ext4_fc_replay_del_range.isra.0.cold (STB_LOCAL)
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
</ul>
