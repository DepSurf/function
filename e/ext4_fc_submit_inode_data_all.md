# Function: <code>ext4_fc_submit_inode_data_all</code>

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
In fs/ext4/fast_commit.c (ffffffff81456180)
Location: fs/ext4/fast_commit.c:918
Inline: True
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
```
**Symbols:**

```
ffffffff81456180-ffffffff814562c8: ext4_fc_submit_inode_data_all.isra.0 (STB_LOCAL)
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
In fs/ext4/fast_commit.c (ffffffff8145bc49)
Location: fs/ext4/fast_commit.c:918
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
In fs/ext4/fast_commit.c (ffffffff814af35a)
Location: fs/ext4/fast_commit.c:891
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
In fs/ext4/fast_commit.c (ffffffff81536d26)
Location: fs/ext4/fast_commit.c:971
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
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
In fs/ext4/fast_commit.c (ffffffff815d51c6)
Location: fs/ext4/fast_commit.c:961
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
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
In fs/ext4/fast_commit.c (ffffffff8160cd7d)
Location: fs/ext4/fast_commit.c:961
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
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
In fs/ext4/fast_commit.c (ffffffff81645b3d)
Location: fs/ext4/fast_commit.c:961
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
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
