# Function: <code>ext4_fc_replay_add_range</code>

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
int ext4_fc_replay_add_range(struct super_block *sb, struct ext4_fc_tl *tl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454f70)
Location: fs/ext4/fast_commit.c:1640
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81454f70-ffffffff81455232: ext4_fc_replay_add_range (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff8145a690)
Location: fs/ext4/fast_commit.c:1640
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff8145a690-ffffffff8145a972: ext4_fc_replay_add_range.constprop.0 (STB_LOCAL)
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
Location: fs/ext4/fast_commit.c:1628
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814ae840-ffffffff814aeb27: ext4_fc_replay_add_range.constprop.0 (STB_LOCAL)
ffffffff81cce2bd-ffffffff81cce2e4: ext4_fc_replay_add_range.constprop.0.cold (STB_LOCAL)
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
Location: fs/ext4/fast_commit.c:1708
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815376b0-ffffffff815379e3: ext4_fc_replay_add_range.constprop.0 (STB_LOCAL)
ffffffff81e812e4-ffffffff81e81307: ext4_fc_replay_add_range.constprop.0.cold (STB_LOCAL)
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
Location: fs/ext4/fast_commit.c:1718
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815d5880-ffffffff815d5bab: ext4_fc_replay_add_range.constprop.0 (STB_LOCAL)
ffffffff820711b0-ffffffff820711d3: ext4_fc_replay_add_range.constprop.0.cold (STB_LOCAL)
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
Location: fs/ext4/fast_commit.c:1718
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff8160d440-ffffffff8160d76b: ext4_fc_replay_add_range.isra.0 (STB_LOCAL)
ffffffff820f0e96-ffffffff820f0eb9: ext4_fc_replay_add_range.isra.0.cold (STB_LOCAL)
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
Location: fs/ext4/fast_commit.c:1718
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81646200-ffffffff8164652b: ext4_fc_replay_add_range.isra.0 (STB_LOCAL)
ffffffff821ce04d-ffffffff821ce070: ext4_fc_replay_add_range.isra.0.cold (STB_LOCAL)
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
