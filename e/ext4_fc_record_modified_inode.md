# Function: <code>ext4_fc_record_modified_inode</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81454030)
Location: fs/ext4/fast_commit.c:1432
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81454030-ffffffff814540d7: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff81459960)
Location: fs/ext4/fast_commit.c:1429
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81459960-ffffffff81459a03: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff814ada50)
Location: fs/ext4/fast_commit.c:1404
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814ada50-ffffffff814adaf1: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff81535dd0)
Location: fs/ext4/fast_commit.c:1484
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81535dd0-ffffffff81535e85: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff815d4290)
Location: fs/ext4/fast_commit.c:1488
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815d4290-ffffffff815d4345: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff8160be80)
Location: fs/ext4/fast_commit.c:1488
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8160be80-ffffffff8160bf35: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff81644c40)
Location: fs/ext4/fast_commit.c:1488
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81644c40-ffffffff81644cf5: ext4_fc_record_modified_inode.isra.0 (STB_LOCAL)
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
